# @flywheel-jp/tsconfig

[![](https://img.shields.io/npm/v/@flywheel-jp/tsconfig)](https://www.npmjs.com/package/@flywheel-jp/tsconfig)

> Shared [TypeScript config](https://www.typescriptlang.org/docs/handbook/tsconfig-json.html) for [FLYWHEEL](https://flywheel.jp/).

## Installation

```
$ yarn add --dev @flywheel-jp/tsconfig
```

## Usage

This package provides several tsconfig:

* `"@flywheel-jp/tsconfig"` - Base config.
* `"@flywheel-jp/tsconfig/nodejs10"` - For Node.js v10 project.
* `"@flywheel-jp/tsconfig/nodejs12"` - For Node.js v12 project.
* `"@flywheel-jp/tsconfig/browser"` - For browser project.

Once the `@flywheel-jp/tsconfig` package is installed, you can use it by specifying the package in the `extends` section of your tsconfig.json.

```jsonc
{
    "extends": "@flywheel-jp/tsconfig/browser",
    // ...
}
```

## License

MIT © FLYWHEEL Inc.
