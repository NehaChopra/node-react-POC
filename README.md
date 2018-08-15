# Node API that feeds a React UI

Project SetUp:

1. Node (9.5.0) [Update node version using package manager via command npm install node-latest-version --save]
2. npm (6.3.0) [Update npm latest version by commnad npm install npm@latest -g]
3. create-react-app (npm package)
4. express-generator (npm package)
5. Okta developer account [Single Sign-On authentiation https://developer.okta.com]
6. npm i -g create-react-app express-generator
7. Scaffold the application using generators
  express backend [NodeJS and Express application]
  create-react-app frontend [React application]
8. In backend folder bin/www change port to 3001 and later run npm install to install the dependencies.
9. In frontend folder package.json add "proxy": "http://localhost:3001" to proxy the client api request to server api, later run yarn install to install the dependencies.
10. https://www.sitepoint.com/yarn-vs-npm/
