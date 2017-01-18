# Doublechin - ESLint Shareable Config
[![travis][travis-image]][travis-url]
[![npm][npm-image]][npm-url]
[![downloads][downloads-image]][downloads-url]

[travis-image]: https://img.shields.io/EtherTyper/eslint-config-doublechin/master.svg
[travis-url]: https://travis-ci.org/EtherTyper/eslint-config-doublechin
[npm-image]: https://img.shields.io/npm/v/eslint-config-doublechin.svg
[npm-url]: https://npmjs.org/package/eslint-config-doublechin
[downloads-image]: https://img.shields.io/npm/dm/eslint-config-doublechin.svg
[downloads-url]: https://npmjs.org/package/eslint-config-doublechin

#### An ESLint [Shareable Config](http://eslint.org/docs/developer-guide/shareable-configs) for [JavaScript Doublechin Style](https://github.com/EtherTyper/doublechin)

This module is for advanced users. You probably want to use [`doublechin`](https://github.com/EtherTyper/doublechin) instead :)))

[![js-doublechin-style](https://cdn.rawgit.com/EtherTyper/doublechin/master/badge.svg)](https://github.com/EtherTyper/doublechin)

## Install

```bash
npm install eslint-config-doublechin
```

## Usage

Shareable configs are designed to work with the `extends` feature of `.eslintrc` files.
You can learn more about
[Shareable Configs](http://eslint.org/docs/developer-guide/shareable-configs) on the
official ESLint website.

To use the JavaScript Happiness Style shareable config, first run this:

```bash
npm install eslint-config-doublechin eslint-plugin-standard eslint-plugin-promise
```

Then, add this to your .eslintrc file:

```
{
  "extends": "doublechin"
}
```

*Note: We omitted the `eslint-config-` prefix since it is automatically assumed by ESLint.*

You can override settings from the shareable config by adding them directly into your
`.eslintrc` file.

### Looking for something easier than this?

The easiest way to use JavaScript Happiness Style to check your code is to use the
[`doublechin`](https://github.com/EtherTyper/doublechin) package. This comes with a global
Node command line program (`doublechin`) that you can run or add to your `npm test` script
to quickly check your style.

## Badge

Use this in one of your projects? Include one of these badges in your readme to
let people know that your code is using the happiness style.

[![js-doublechin-style](https://cdn.rawgit.com/EtherTyper/doublechin/master/badge.svg)](https://github.com/EtherTyper/doublechin)

```markdown
[![js-doublechin-style](https://cdn.rawgit.com/EtherTyper/doublechin/master/badge.svg)](https://github.com/EtherTyper/doublechin)
```

[![js-doublechin-style](https://img.shields.io/badge/code%20style-doublechin-brightgreen.svg)](https://github.com/EtherTyper/doublechin)

```markdown
[![js-doublechin-style](https://img.shields.io/badge/code%20style-doublechin-brightgreen.svg)](https://github.com/EtherTyper/doublechin)
```

## Learn more

For the full listing of rules, editor plugins, FAQs, and more, visit the main
[JavaScript Doublechin Style repo](https://github.com/EtherTyper/doublechin).

## License

MIT. Copyright (c) [Eli Bradley](http://github.ethertyper.com/).
