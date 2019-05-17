# vuepress-plugin-live

Make your markdown code examples come alive using [vue-live](vue-styleguidist/vue-live)

[![Build Status](https://travis-ci.com/vue-styleguidist/vuepress-plugin-live.svg?branch=master)](https://travis-ci.com/vue-styleguidist/vuepress-plugin-live)
[![NPM Version](https://img.shields.io/npm/v/vuepress-plugin-live.svg)](https://www.npmjs.com/package/vuepress-plugin-live) [![NPM Downloads](https://img.shields.io/npm/dm/vuepress-plugin-live.svg)](https://www.npmjs.com/package/vuepress-plugin-live)
[![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg)](https://github.com/semantic-release/semantic-release)

## Install

```sh
yarn add -D vuepress-plugin-live
# or with npm:  npm install -D vuepress-plugin-live
```

## Config

```js
//.vuepress/config.js
module.exports = {
  //...
  plugins: [
    ["live"],
  ]
}
```

## Usage

In your markdown file just add a `live` flag to your fenced code blocks.

<pre><code>```vue live
&lt;button&gt;example&lt;/button&gt;
```
</code></pre>
