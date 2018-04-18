## [React & Webpack 4 From Scratch - No CLI](https://www.youtube.com/watch?v=deyxI-6C2u4) by [Brad Traversy](https://www.traversymedia.com)
## A React App Boilerplate

&nbsp;
### 01 Dependencies

* `$ npm init`
* `$ yarn add react react-dom`
* `$ yarn add -D webpack webpack-dev-server webpack-cli`
* `$ yarn add -D babel-core babel-loader babel-preset-env babel-preset-react html-webpack-plugin`


&nbsp;
### 02 Config Webpack

* webpack.config.js
* .babelrc
* src/index.html


&nbsp;
### 03 Start and Build

* src/index.js
* components/App.js
* Add *start* and *build* scripts to *package.json*.

    *  `$ npm start` starts *webpack-dev-server* for development.

    *  `$ npm run build` creates the *dist* folder which contains a build for the app that can be used autonomously in production.


&nbsp;
### 04 Spread and CSS

* Edit .babelrc (add "stage-2") to support the spread operator usage.

* Add CSS support:
  * `$ yarn add css-loader style-loader`
  * Edit webpack.config.js.
