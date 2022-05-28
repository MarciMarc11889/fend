# Project Desciption

This project is made by myself. This project should practice the following points:

- Setting up Webpack
- Sass styles
- Webpack Loaders and Plugins
- Creating layouts and page design
- Service workers
- Using APIs and creating requests to external urls

This poject uses NLP. NLP stands for:

> Natural language processing (NLP) is a subfield of computer science, information engineering, and artificial intelligence
concerned with the interactions between computers and human (natural) languages, in particular how to program computers to
process and analyze large amounts of natural language data.

## How-to run the app



At first split the terminal and run 
```
npm run build-dev
```

in the first terminal. Then run
```
npm run build-prod
```
in the second terminal to set up the dist folder.

After that type
```
npm start
```
into the second terminal to start the prod server.

## Dependencies

Here are the needed dependencies and versions:

```
"dependencies": {
"dotenv": "^8.2.0",
"express": "^4.17.1",
"jest-fetch-mock": "^3.0.3",
"webpack": "^4.35.3",
"webpack-cli": "^3.3.5"
},
"devDependencies": {
"@babel/core": "^7.13.15",
"@babel/plugin-transform-modules-commonjs": "^7.13.8",
"@babel/preset-env": "^7.13.15",
"babel-loader": "^8.2.2",
"body-parser": "^1.19.0",
"clean-webpack-plugin": "^3.0.0",
"cors": "^2.8.5",
"css-loader": "^5.2.1",
"html-webpack-plugin": "^3.2.0",
"jest": "^26.6.3",
"mini-css-extract-plugin": "^1.4.1",
"node-fetch": "^2.6.1",
"node-sass": "^5.0.0",
"optimize-css-assets-webpack-plugin": "^5.0.4",
"sass": "^1.32.8",
"sass-loader": "^10.1.1",
"style-loader": "^2.0.0",
"terser-webpack-plugin": "^5.1.1",
"webpack-dev-server": "^3.11.2",
"workbox-webpack-plugin": "^6.1.5"
}
```