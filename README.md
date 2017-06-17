# eslint-config-posrix

Personal workspace Eslint config

## Installation

```
yarn add eslint-config-posrix --dev
```
or npm

```
npm install eslint-config-posrix --save-dev
```

## Usage

Create a `.eslintrc` file to extend the ruleset.

```json
{
    "extends": "posrix"
}
```

If you're using React in your project, you'll need to extend the React extension of the configuration.

```json
{
    "extends": "posrix/react"
}
```

If you're using Vue in your project, you'll need to extend the Vue extension of the configuration.

```json
{
    "extends": "posrix/vue"
}
```

### Globals

```json
{
    "globals": {
        "$": true
    }
}
```

### Environments

```json
{
    "env": {
      "browser": true,
      "node": true
    }
}
```

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
