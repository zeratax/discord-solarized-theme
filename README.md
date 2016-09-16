#Solarized - **WIP**
Discord theme based on https://github.com/altercation/solarized

##Install
You have to options to use this theme:

**1.**  Use **BetterDiscord** and put the [.theme.css file](https://raw.githubusercontent.com/ZerataX/discord-solarized-theme/master/solarizeds.theme.css) in the `/BetterDiscord/themes/` folder or use [evenBetterRepo](https://github.com/IRDeNial/BD-Even-Better-Repo)

**2.**  Install something like **Stylish**

**[Chrome](https://chrome.google.com/webstore/detail/stylish/fjnbnpbmkenffdnngjfgmeleoegfcffe?hl=de)**

**[Firefox](https://addons.mozilla.org/de/firefox/addon/stylish/)**
    
##Config
Use the [.sass file](https://raw.githubusercontent.com/ZerataX/discord-solarized-theme/master/solarized.sass) to quickly change the colorscheme.
Now you just need to recompile the css.
You again have to options:

**1.** Install ruby, then

```
gem install sass
sass --update solarized.sass:solarized.theme.css
```

add `--style compressed' to create a minified css

**you may need to adjust your `$PATH` to include ruby gem**

**your theme will not be automatically updated if you compile it yourself**

**2.** http://www.sassmeister.com/ and __make sure your syntax is set to *sass*__

and add the meta tag at the top if you want to use it for **BetterDiscord**, e.g.

`//META{"name":"Solarized","description":"solarized theme for discord","author":"ZerataX","version":"0.1"}//`

##Screenshots
###Dark appearance
![dark appearance](https://my.mixtape.moe/buwper.png)
###Light appearance
![light appearance](https://my.mixtape.moe/dnhjdz.png)

