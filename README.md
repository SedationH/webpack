https://www.taniarascia.com/how-to-use-webpack/



### Babel (JavaScript)

[Babel](https://babeljs.io/) is a tool that allows us to use tomorrow's JavaScript, today.

We're going to set up a rule that checks for any `.js` file in the project (outside of `node_modules`) and uses the `babel-loader` to transpile. There are a few additional dependencies for Babel as well.

- [`babel-loader`](https://webpack.js.org/loaders/babel-loader/) - Transpile files with Babel and webpack.
- [`@babel/core`](https://www.npmjs.com/package/@babel/core) - Transpile ES2015+ to backwards compatible JavaScript
- [`@babel/preset-env`](https://babeljs.io/docs/en/babel-preset-env) - Smart defaults for Babel
- [`@babel/plugin-proposal-class-properties`](https://babeljs.io/docs/en/babel-plugin-proposal-class-properties) - An example of a custom Babel config (use properties directly on a class)****

> If you're setting up a TypeScript project, you would use the `typescript-loader` instead of `babel-loader` for all your JavaScript transpiling needs. You would check for `.ts` files and use `ts-loader`.

