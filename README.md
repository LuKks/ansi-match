# ansi-match

Regular expression for matching ANSI escape codes.

```
npm i ansi-match
```

## Usage
```javascript
const ansi = require('ansi-match')

const colors = '\x1B[31mred\x1B[39m'
console.log(colors.replace(ansi, '')) // => 'red'
```

Simplified fork of [ansi-regex](https://github.com/chalk/ansi-regex).

## License
MIT
