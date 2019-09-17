# Babel

## Installation

`npm install --save-dev @babel/core @babel/cli @babel/preset-env`

`npm install --save @babel/polyfill`

## Babel cli

`./node_modules/.bin/babel src --out-dir lib`

## Presets ( React )

`npm install --save-dev @babel/preset-react`

[https://babeljs.io/docs/en/babel-preset-react](https://babeljs.io/docs/en/babel-preset-react)

```./node_modules/.bin/babel src --out-dir lib

WARNING: We noticed you're using the `useBuiltIns` option without declaring a core-js versio
n. Currently, we assume version 2.x when no version is passed. Since this default version wi
ll likely change in future versions of Babel, we recommend explicitly setting the core-js ve
rsion you are using via the `corejs` option.

You should also be sure that the version you pass to the `corejs` option matches the version
 specified in your `package.json`'s `dependencies` section. If it doesn't, you need to run o
ne of the following commands:

  npm install --save core-js@2    npm install --save core-js@3
  yarn add core-js@2              yarn add core-js@3

Successfully compiled 1 file with Babel.
```

## Webpack Babel JSX

[https://webpack.js.org/configuration/configuration-languages/#babel-and-jsx](https://webpack.js.org/configuration/configuration-languages/#babel-and-jsx
)