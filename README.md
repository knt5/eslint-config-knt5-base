# eslint-config-knt5-base

A personal ESLint config based on eslint-config-airbnb-base

## Installation

```
npm install --save-dev eslint-config-knt5-base
```

## Usage

### .eslintrc

```
{
  "extends": ["eslint-config-knt5-base"]
}
```

### .eslintrc.js

```
module.exports = {
	extends: [
		'eslint-config-knt5-base'
	]
};
```

### package.json

```
{
  "scripts": {
    "lint": "eslint ."
  },
  "devDependencies": {
    "eslint": "^3.9.1",
    "eslint-config-knt5-base": "^1.0.0"
  }
}
```

Lint with ```npm run lint```.
