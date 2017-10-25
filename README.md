# eslint-config-esmanning

**ESLint [Shareable Config](http://eslint.org/docs/developer-guide/shareable-configs) for JavaScript [Manning](https://github.com/dlmanning) Style**

[![latest version][npm-img]][npm-url]

[npm-img]: https://img.shields.io/npm/v/eslint-config-esmanning.svg?style=flat-square
[npm-url]: https://www.npmjs.com/package/eslint-config-esmanning

## Install

```bash
npm install eslint eslint-config-esmanning --save-dev
echo "{ \"extends\": [\"esmanning\"] }" > .eslintrc
npx npe scripts.test "eslint ."
```

## Usage

Shareable configs are designed to work with the `extends` feature of `.eslintrc` files.
You can learn more about
[Shareable Configs](http://eslint.org/docs/developer-guide/shareable-configs) on the
official ESLint website.

To use the JavaScript Manning Style shareable config, just add this to your .eslintrc file:

```json
{
  "extends": "esmanning"
}
```

*Note: `eslint-config-` prefix is automatically assumed by ESLint.*

You can override settings from the shareable config by adding them directly into your
`.eslintrc` file.

`eslint-config-esmanning` also installs the following so you don't have to:

- eslint-config-standard
- eslint-config-standard-react
- eslint-plugin-promise
- eslint-plugin-react
- eslint-plugin-standard

This may not be the way you want to do things in your own project. This is for the sake of convenience for ZHealth's projects (one declared dependency instead of seven).

## License

[MIT](LICENSE)
