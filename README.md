# eslint-config-koa
[![NPM version](https://img.shields.io/npm/v/eslint-config-koa.svg?style=flat-square)](https://www.npmjs.com/package/eslint-config-koa)
[![build status](https://img.shields.io/travis/koajs/eslint-config-koa/master.svg?style=flat-square)](https://travis-ci.org/koajs/eslint-config-koa)
[![dependency status](https://img.shields.io/david/dev/koajs/eslint-config-koa.svg?style=flat-square)](https://david-dm.org/koajs/eslint-config-koa?type=dev)
[![downloads](https://img.shields.io/npm/dm/eslint-config-koa.svg?style=flat-square)](https://www.npmjs.com/package/eslint-config-koa)

[Koa](https://www.npmjs.com/package/koa)'s ESLint config, based on [Standard](https://www.npmjs.com/package/eslint-config-standard)

This is recommended for [Koa packages](https://github.com/koajs). It can be used for your own packages if you want, but be aware that [Standard](https://www.npmjs.com/package/eslint-config-standard) is more generic.

## Usage
Shareable configs are designed to work with the `extends` feature of `.eslintrc` files.
You can learn more about
[Shareable Configs](http://eslint.org/docs/developer-guide/shareable-configs) on the
official ESLint website.

To use the Koa shareable config, first run this:

```bash
npm install --save-dev eslint-config-koa eslint-config-standard eslint-plugin-standard eslint-plugin-promise eslint-plugin-import eslint-plugin-node
```

Then, add this to your .eslintrc file:

```
{
  "extends": "koa"
}
```

*Note: We omitted the `eslint-config-` prefix since it is automatically assumed by ESLint.*

You can override settings from the shareable config by adding them directly into your
`.eslintrc` file.
