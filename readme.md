# jsDriver Library

## download new package

```bash
bun install newpackage
```

### create new package file

e.g., iconv.js

```
window.iconv=require('iconv-lite');
```

## package js with dependency to one target file

```
browserify -o js-lib/iconv.js iconv.js
```

## push to github and change url to jsDriver

[Migrate from GitHub to jsDelivr](https://www.jsdelivr.com/github)

## find the final url, install it on Appsmith

Packages url: https://cdn.jsdelivr.net/gh/yylonly/jsDelivr/

final iconv package url

[cdn.jsdelivr.net/gh/yylonly/jsDelivr@master/js-lib/iconv.js](https://cdn.jsdelivr.net/gh/yylonly/jsDelivr@master/js-lib/iconv.js)
