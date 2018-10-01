<h1 align="center">rollup-plugin-vue-svg</h1>
<p align="center">Rollup plugin that allows to use SVG files as Vue Components</p>

## Instalation

[![Greenkeeper badge](https://badges.greenkeeper.io/visualfanatic/rollup-plugin-vue-svg.svg)](https://greenkeeper.io/)

``` bash
npm i -D rollup-plugin-vue-svg

yarn add --dev rollup-plugin-vue-svg
```

## Usage
``` js
import vue from 'rollup-plugin-vue';
import vueSvg from 'rollup-plugin-vue-svg';

export default {
  // ...
  plugins: [
    vue(),
    vueSvg(),
  ],
  // ...
};
```
