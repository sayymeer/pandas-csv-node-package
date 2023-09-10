# pandas-csv-node

This is a NodeJS package which provide functionality similar to `read_csv()` function in python pandas library

## Installation

This is a NodeJS module available through npm-registry. Installation is done using `npm install` command.

```sh
npm install pandas-csv-node
```

## API

```js
import {readCsv} from "pandas-csv-node"
```

### readCsv

`readCsv` takes two argument one is `filePath` and other is `encoding`, by default encoding is set to `utf-8`.