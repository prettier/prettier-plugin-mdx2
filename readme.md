# @prettier/plugin-mdx2

[![Npm Version](https://img.shields.io/npm/v/@prettier/plugin-mdx2.svg?style=flat-square)](https://www.npmjs.com/package/@prettier/plugin-mdx2)
[![MIT License](https://img.shields.io/npm/l/@prettier/plugin-mdx2.svg?style=flat-square)](https://github.com/prettier/prettier/blob/main/license)

> Prettier plugin for MDX2.

> [!IMPORTANT]
> This plugin extracted for MDX2 users from prettier<=3.7.
>
> Please migrate to MDX3, and use the builtin parser if possible.
>
> This plugin only change if bugs found, won't add any new features.

## Install

```bash
yarn add --dev --exact prettier @prettier/plugin-mdx2
```

## Usage

Create or modify your [prettier configuration file](https://prettier.io/docs/en/configuration) to use the plugin:

```js
// prettier.config.mjs
import * as prettierPluginMdx2 from "@prettier/plugin-mdx2";

/**
 * @see https://prettier.io/docs/configuration
 * @type {import("prettier").Config}
 */
const config = {
  plugins: [prettierPluginMdx2],
};

export default config;
```

