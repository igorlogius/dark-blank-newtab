# dark-blank-newtab a firefox/chrome webextension add-on

## Details:
https://addons.mozilla.org/en-US/firefox/addon/dark-blank-newtab/

## Usage:  
wget https://github.com/igorlogius/tbl2csv/archive/master.zip
unzip master.zip
zip -j "dark-blank-newtab-$(grep '"version"' dark-blank-newtab-master/src/manifest.json  | cut -d'"' -f4).xpi" ./dark-blank-newtab-master/src/*
```
Import dark-blank-newtab-x.y.z.zip into your browser (e.g. via `about:debugging`)
