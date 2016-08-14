# pug-lint-config-migration-v2

[pug-lint] configuration for migration to Pug 2.

## How to use

First, install [pug-lint] and this configuration package:

```sh
$ npm i --save-dev pug-lint pug-lint-config-migration-v2
```

Next, add a `.pug-lintrc.json` file in your project root:

```json
{
  "extends": "migration-v2"
}
```

And now, when you execute `pug-lint`, you should see a list of errors that might prevent your app from working properly in Pug 2.

[pug-lint]: https://www.npmjs.com/package/pug-lint
