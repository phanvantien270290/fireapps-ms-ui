# @manysale/fontawesome-common-types - SVG with JavaScript

> "I came here to chew bubblegum and install Font Awesome 5 - and I'm all out of bubblegum"

[![npm](https://img.shields.io/npm/v/@manysale/fontawesome-common-types.svg?style=flat-square)](https://www.npmjs.com/package/@manysale/fontawesome-common-types)

## What is this package?

Font Awesome 5 JavaScript packages support TypeScript. This package abstracts out some of the common definitions that those packages use.

## Here be dragons

If you are trying to import types from this package we _highly_ recommend you do the following instead as _all types in this package are re-exported to the main fontawesome package_.

your.ts

```
import {
  IconName
} from `@manysale/fontawesome-svg-core`

const myIcon: IconName = "..."
```

## Issues and support

Start with [GitHub issues](https://github.com/manysale/Font-Awesome/issues) and ping us on [Twitter](https://twitter.com/fontawesome) if you need to.
