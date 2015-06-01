# turkish-suffixes

## how to install

### npm
```sh
npm install turkish-suffixes --save
```

## how to use
### node
```js
var ts = require('turkish-suffixes');
```

#variables & values
```text
suffix -> "in", "e", "i", "de", "den", "ile"

apostrof -> true, false (if use false apostrof don't show)

apostrofMark -> "'","`"
```

## examples
```js
ts("İstanbul", "de", true, "'"); //İstanbul'da
ts("büyük masa", "de", false, "'"); //büyük masada
ts("Atatürk", "in", true, "`"); // Atatürk`ün
```
