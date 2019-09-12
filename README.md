# Eslint-config-atol

## Install

npm: 

```bash
# 1. Install peer dependencies
npm i babel-eslint eslint eslint-config-airbnb eslint-plugin-import eslint-plugin-react --save-dev

# 2. Install package
npm i @atol/eslint-config-atol --save-dev
```

# Usage

Update `.eslintrc.js`:

```js
module.exports = {
    extends: ['@atol/eslint-config-atol'],
    rules: {
      // ... Add your rules
    }
};
```

