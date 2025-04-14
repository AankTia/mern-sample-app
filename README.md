## Intall Depenedencies

```bash
npm install express mongodb react react-dom
```

Development dependencies

```bash
npm install --save-dev babel-core babel-loader babel-preset-env babel-preset-react babel-preset-stage-2 nodemon webpack webpack-cli webpack-dev-middleware webpack-hot-middleware webpack-node-externals
```

## Start Server for Development

```bash
npm run development
```

This command will get Nodemon, Webpack, and the server started for development

## Start Server for Production

```bash
npm run build
```

This will generate the client and server code bundles for production mode (before running this script, make sure to remove the devBundle.compile code from server.js)

```bash
npm run start
```

This command will run the bundled code in production
