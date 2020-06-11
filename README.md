## Try this:

```sh
dconf reset -f "/com/premiumsoft/navicat-premium/" && rm -Rf ~/.config/navicat/Premium/preferences.json*
```
And re-run .AppImage executable.


or

sudo nano /usr/local/bin/lauch-navicat.sh

paste this:
```
#!/bin/sh
dconf reset -f "/com/premiumsoft/navicat-premium/" && rm -Rf ~/.config/navicat/Premium/preferences.json*
/Path/To/navicat.AppImage
```

sudo chmod +x /usr/local/bin/lauch-navicat.sh

$ lauch-navicat.sh

Works with Navicat 15 on ubuntu 20.04.


### DISCLAIMER
Please Navicat, create an free tool to poor users =)
