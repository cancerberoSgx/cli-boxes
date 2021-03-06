# cli-boxes [![Build Status](https://travis-ci.org/sindresorhus/cli-boxes.svg?branch=master)](https://travis-ci.org/sindresorhus/cli-boxes)

> Boxes for use in the terminal

The list of boxes is just a [JSON file](boxes.json) and can be used anywhere.


## Install

```
$ npm install cli-boxes
```


## Usage

```js
const cliBoxes = require('cli-boxes');

console.log(cliBoxes.single);
/*
{
    topLeft: '┌',
    topRight: '┐',
    bottomRight: '┘',
    bottomLeft: '└',
    vertical: '│',
    horizontal: '─''
}
*/
```


## API

### cliBoxes

#### `single`

```
┌────┐
│    │
└────┘
```

#### `double`

```
╔════╗
║    ║
╚════╝
```

#### `round`

```
╭────╮
│    │
╰────╯
```

#### `singleDouble`

```
╓────╖
║    ║
╙────╜
```

#### `doubleSingle`

```
╒════╕
│    │
╘════╛
```

#### `classic`

```
+----+
|    |
+----+
```


## Related

- [boxen](https://github.com/sindresorhus/boxen) - Create boxes in the terminal


## License

MIT © [Sindre Sorhus](https://sindresorhus.com)
