# Vite Plugin Eruda

> A vite plugin help you automatically open debugging tools in the development environment

### Install
```sh
$ yarn add vite-plugin-eruda
```

### Usage
```javascript
import eruda from 'vite-plugin-eruda'


module.exports = {
  plugins: [
    // others
    eruda()
  ]
}
```

### Options

#### `debug`

- **Type:** `boolean | undefind`
- **Default:** `'undefind'`

  Optional. If not, process.env.node will be used by default `process.env.NODE_ENV !== "production"` standard opens the debugging mode. If there is, this parameter takes precedence.

#### `url`

- **Type:** `string | undefind`
- **Default:** `'undefind'`
  eruda url。不传值，默认使用 https://cdn.jsdelivr.net/npm/eruda

### License
MIT
