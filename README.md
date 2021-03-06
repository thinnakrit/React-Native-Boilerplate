# React Native Boilerplate
This is react-native starter boilerplate for client
# Features

- [React](https://github.com/facebook/react)
- [React-Native](https://facebook.github.io/react-native/docs/)
- Native-Base
- React-Native-Redux
- Redux
- React-Native-Router

# Getting Started
```
$ npm install -g react-native-cli
$ git clone https://github.com/thinnakrit/React-Native-Boilerplate.git AwesomeProject
$ react-native init AwesomeProject
$ cd AwesomeProject

```

# Setup For run on Web
```
$ npm i react react-dom react-native-web --save
$ npm i webpack babel-loader babel-preset-react babel-preset-es2015 --save
$ npm i webpack-dev-server --save-dev

```
# Copy File and Edit for use (Replace "You App Name")
```
+- ./app
+- index.web.js
+- index.ios.js
+- index.android.js
+- index.html
+- webpack.config.js

```
# Start and Test on Android
```
cmd >> react-native run-android
```
# Start and Test on IOS
```
cmd >> react-native run-ios
```
# Start and Test on Web

Now, just run 
```
cmd >> ./node_modules/.bin/webpack-dev-server --inline 
```
to start webpack, and open your browser to http://localhost:8080/. Fingers crossed, you will see a familiar welcome message but in the browser!

Thank you for your suggestions!
