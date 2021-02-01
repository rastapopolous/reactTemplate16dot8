# reactTemplate16dot8 

**A fully functional modern out-of-the-box react template**

**Includes:**

+ react 16.8 HOOKS!!!
  
+ router4
  
+ axios for api calls

+ other great stuff: poppers, styledComponents, sass-configured

+ webpack bundles all major assets -- css/scss jpg/gif/png svg 

+ serves locally with webpack-dev-server 
  
+ webpack, eslint fully configured for react
  
+ sourcemap configured to view and set breakpoints on jsx files in console sources
  
# Setting up the react app

## install node.js
- https://nodejs.org/en/

## install yarn 
```
$ sudo chown -R $USER /usr/local/lib/node_modules
$ npm install -g yarn
```

## running the app
```
$ cd into getccd-react-app
$ yarn install
$ yarn start
```

### `yarn start`

Runs the app in the development mode.<br />
Open [http://localhost:8080] to view it in the browser.

### `yarn test`

Launches the test runner in the interactive watch mode.<br />
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

+ Webpack Hot Module Replacement (HMR) dynamically updates modules as they as they modify. 

+ index_bundle.js, non-minified, is available in /dist. By default environment variable is not configured.

+ Your app is ready to be deployed!