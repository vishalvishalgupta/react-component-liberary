Starting the project folder:

  1. mkdir react-sample-components-library
  2. cd react-sample-components-library
  3. npm init -y

Installing dependencies:
  1. npm install --save-dev react react-dom @emotion/core @emotion/styled
  2. npm install --save-dev react-styleguidist webpack
  3. npm install --save-dev babel-loader @babel/core @babel/preset-env @babel/preset-react
  
Basic configuration in .babelrc file: 

  {                           
   "presets": ["@babel/preset-env", "@babel/preset-react"]                       
  }
  
Add ”start”: “styleguidist server” to package.json

Now, you can simply write $ npm start and you’ll gain a web server on port 6060 where you can review your progress.
