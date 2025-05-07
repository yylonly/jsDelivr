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
browserify -o js-lib/iconv.js index.js
```

## push to github and change url to jsDriver

[Migrate from GitHub to jsDelivr](https://www.jsdelivr.com/github)

## find the final url, install it on Appsmith

> [jsDelivr/js-lib/iconv.js at main · yylonly/jsDelivr](https://github.com/yylonly/jsDelivr/blob/main/js-lib/iconv.js)
