npm init
npm install webpack --save -dev
webpack MUST see a webpack.config.js file

remember to require('path') to get access to absolute path using node built in features

change package.json "scripts"  to use "build": "webpack"

npm run build  //starts webpack

---- LOADERS ----