# Personal ESLint Config

<a href="https://github.com/dragunovartem99/eslint-config/blob/main/index.js" target="_blank"><img alt="Static Badge" src="https://img.shields.io/badge/View_Configuration-red"></a>
<img alt="NPM Version" src="https://img.shields.io/npm/v/@dragunovartem99/eslint-config?color=orange">

## Installation

```shell
npm install --save-dev @dragunovartem99/eslint-config
```

## Usage

1. Add the configuration to your project's `package.json`:

```json
{
    "scripts": {
	  	  "lint": "eslint",
        "lint:fix": "eslint --fix"
    },
}
```

2. Create `eslint.config.js` at root level of your project:

```js
export { default } from "@dragunovartem99/eslint-config";
```

3. Run the linter:

```shell
npm run lint
```

Or try to fix as many issues as possible:

```shell
npm run lint:fix
```

## Creating your own configuration

For creating similar configurations, see:

- [Official ESLint plugin for Vue.js](https://eslint.vuejs.org/)
- [npm's documentation on scoped packages](https://docs.npmjs.com/creating-and-publishing-scoped-public-packages)
