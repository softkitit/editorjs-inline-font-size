![](https://badgen.net/badge/Editor.js/v2.0/blue)

# Font Size tool
Font size inline tool for the [Editor.js](https://editorjs.io).

## Installation

### Install via NPM or Yarn

Get the package

```shell
yarn add editorjs-inline-font-size-tool
```

Include module in your application

```javascript
const FontSize = require('editorjs-inline-font-size-tool');
```

## Usage
Add a new Tool to the `tools` property of the Editor.js initial config.

```javascript
var editor = EditorJS({
  ...
  
  tools: {
    ...
    fontSize: FontSize,
    config: {
      fontSizeList: [
        { label: '10', value: '1', class: 'fs-1' },
        { label: '13', value: '2', class: 'fs-2' },
      ],
    },
  }
  ...
});
```




