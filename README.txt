Paso 1

mkdir webpack-demo
cd webpack-demo
npm init -y
npm install webpack webpack-cli --save-dev

Paso 2 
npm install --save lodash
npx webpack

Paso 3 config
npx webpack --config webpack.config.js

Alias for "npx web pack"
npm run build

Adding CSS
npm install --save-dev style-loader css-loader

Loading data
npm install --save-dev csv-loader xml-loader
npm install toml yamljs json5 --save-dev

Removing
npm uninstall css-loader csv-loader json5 style-loader toml xml-loader yamljs

HtmlWebpackPlugin
npm install --save-dev html-webpack-plugin

Develop mode

webpack's Watch Mode
    "watch": "webpack --watch" in package.json scripts
    npm run watch

webpack-dev-server
    npm install --save-dev webpack-dev-server

webpack-dev-middleware