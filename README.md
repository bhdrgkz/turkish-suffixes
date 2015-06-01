# turkish-suffixes

## How to install

### npm
```sh
npm install turkish-suffixes --save
```

## How to use
### NodeJS
```js
var ts = require('turkish-suffixes');
```
#variables
suffix -> "in", "e", "i", "de", "den", "ile"

apostrof -> true, false (if use false apostrof don't show)

apostrofMark -> "'","`"

## Examples
```js
ts("İstanbul", "de", true, "'"); //İstanbul'da
ts("büyük masa", "de", false, "'"); //büyük masada
ts("Atatürk", "in", true, "`"); // Atatürk`ün
```
