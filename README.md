# ESLint Config

This repository provides extensive ESLint configurations designed to be easily adaptable and used in external projects. The configurations cover both React and NodeJS-based projects, ensuring clean, high-quality code.

## About the Repository

ESLint is a linting tool that helps developers maintain a consistent code pattern and identify and fix issues in JavaScript code before execution. This repository was created with the aim of providing a set of robust and versatile configurations for different development environments.

## Installation

To start using the settings from this repository, follow the steps below:

1. Install the package with the following command:

```shell
npm install @lucasaugustsof/eslint-config -D
```
```shell
yarn add @lucasaugustsof/eslint-config -D
```

## Using the settings

After installation, you can reference the settings in your `.eslintrc.js` file:

```js
module.exports = {
  extends: "@lucasaugustsof/eslint-config/react"
  // extends: "@lucasaugustsof/eslint-config/node"
}
```

## Available settings

- [React](https://react.dev/): Optimized settings for React-based projects.
- [NodeJS](https://nodejs.org/en): Specific settings for NodeJS development.

## License

This project is under the MIT license. See the [LICENSE](./LICENSE) file for more details.

<br/>

**Ensure clean, high-quality code in all your projects with these ESLint setups! 🚀🔧**