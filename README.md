# Commitlint config

> Shared Commitlint config for all my projects

## Installation

```bash
  yarn add --dev @albizures/commitlint
```

then in `commitlint.config.js`

```js
module.exports = require('@albizures/commitlint');
```

### Husky setup

In order to check commit messages is necessary to setup husky

```bash
  yarn add --dev husky
  yarn husky install
  yarn husky add .husky/commit-msg 'yarn commitlint --edit "$1"'
```

## Feedback

If you have any feedback, please reach out to me at [@albzrs](https://twitter.com/albzrs)

## License

[MIT](https://choosealicense.com/licenses/mit/)
