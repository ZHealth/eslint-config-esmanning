# eslint-config-esmanning

**ESLint [Shareable Config](http://eslint.org/docs/developer-guide/shareable-configs) JavaScript Manning Style**

## Install

```bash
npm install eslint-config-esmanning --save-dev
```

## Usage

Shareable configs are designed to work with the `extends` feature of `.eslintrc` files.
You can learn more about
[Shareable Configs](http://eslint.org/docs/developer-guide/shareable-configs) on the
official ESLint website.

To use the JavaScript Manning Style shareable config, first run this:

```bash
npm install --save-dev eslint-config-esmanning
```

Then, add this to your .eslintrc file:

```
{
  "extends": "esmanning"
}
```

*Note: We omitted the `eslint-config-` prefix since it is automatically assumed by ESLint.*

You can override settings from the shareable config by adding them directly into your
`.eslintrc` file.

## License

[MIT](LICENSE)
