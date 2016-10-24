# eslint-config-esmanning

**ESLint [Shareable Config](http://eslint.org/docs/developer-guide/shareable-configs) for JavaScript Manning Style**

## Install

```bash
npm install eslint-config-esmanning --save-dev
```

## Usage

Shareable configs are designed to work with the `extends` feature of `.eslintrc` files.
You can learn more about
[Shareable Configs](http://eslint.org/docs/developer-guide/shareable-configs) on the
official ESLint website.

To use the JavaScript Manning Style shareable config, just add this to your .eslintrc file:

```
{
  "extends": "esmanning"
}
```

*Note: We omitted the `eslint-config-` prefix since it is automatically assumed by ESLint.*

You can override settings from the shareable config by adding them directly into your
`.eslintrc` file.

`eslint-config-esmanning` also installs the following so you don't have to:

- eslint
- eslint-config-standard
- eslint-config-standard-react
- eslint-plugin-promise
- eslint-plugin-react
- eslint-plugin-standard

This is probably not the way you want to do things in your own project. This is for the sake of convenience for ZHealth's projects (one declared dependency instead of seven).

## License

[MIT](LICENSE)
