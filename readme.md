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
