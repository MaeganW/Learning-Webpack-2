---- WEBPACK SETUP ----

npm init
npm install webpack --save-dev
webpack MUST see a webpack.config.js file

remember to require('path') to get access to absolute path using node built in features

change package.json "scripts"  to use "build": "webpack"

npm run build  //starts webpack

---- LOADERS (AKA RULES) ----

adding Babel requires 3 modules: 

    'babel-loader' : teaches babel how to use webpack
    
    'babel-core' : takes in code, parses it, generates output files
    
    'babel-preset-env' : rules for how to transform code (the actual brains)
    
npm install --save-dev babel-loader babel-core babel-preset-env

add .babelrc file to root dir to instruct babel