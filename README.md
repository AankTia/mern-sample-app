

## Intall Depenedencies

```bash
npm install express mongodb react react-dom
```

Development dependencies
```bash
npm install --save-dev babel-core babel-loader babel-preset-env babel-preset-react babel-preset-stage-2 nodemon webpack webpack-cli webpack-dev-middleware webpack-hot-middleware webpack-node-externals
```

## Configuring Babel, Webpack, and Nodemon

Before we start coding up the web application, we need to configure Babel,
Webpack, and Nodemon to compile, bundle, and auto reload the changes in
the code during development.

### Babel

Create a `.babelrc` file in your project folder and add the following JSON
with `presets` and `plugins` specified.

```
{
    "presets": [
        "env",
        "stage-2",
        "react"
    ],
    "plugins": [
        "react-hot-loader/babel"
    ]
}
```