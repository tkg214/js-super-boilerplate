# Super JavaScript Stack Boilerplate
# Documentation
* [Node](https://nodejs.org/)
- a JavaScript runtime environment. It is mostly used for Back-End development, but also for general scripting. In the context of Front-End development, it can be used to perform a whole bunch of tasks like linting, testing, and assembling files.
* [Yarn](https://yarnpkg.com/en/)
- a Node.js package manager which is much faster than NPM, has offline support, and fetches dependencies more predictably.
* [Babel](https://babeljs.io/)
- a compiler that transforms ES6 code (and other things like React's JSX syntax) into ES5 code. It is very modular and can be used in tons of different environments. It is by far the preferred ES5 compiler of the React community.
* [ES6](http://es6-features.org/)
- the most significant improvement of the JavaScript language. There are too many ES6 features to list them here but typical ES6 code uses classes with class, const and let, template strings, and arrow functions ((text) => { console.log(text) }).
* [ESLint](http://eslint.org/)
- the linter of choice for ES6 code. A linter gives you recommendations about code formatting, which enforces style consistency in your code, and code you share with your team. It's also a great way to learn about JavaScript by making mistakes that ESLint will catch.
* [ESLint Airbnb](https://www.npmjs.com/package/eslint-config-airbnb)
* [ESLint Compat](https://github.com/amilajack/eslint-plugin-compat)
* [Flow](https://flow.org/)
- a static type checker by Facebook. It detects inconsistent types in your code. For instance, it will give you an error if you try to use a string where should be using a number.
* [Husky](https://github.com/typicode/husky)
- a package that makes this very easy to set up [Git Hooks](https://git-scm.com/book/en/v2/Customizing-Git-Git-Hooks).
* [Express](http://expressjs.com/)
- by far the most popular web application framework for Node. It provides a very simple and minimal API, and its features can be extended with middleware.
* [Compression](https://github.com/expressjs/compression)
- an Express middleware to activate Gzip compression on the server.
* [Nodemon](https://nodemon.io/)
- a utility to automatically restart your Node server when file changes happen in the directory.
* [PM2](http://pm2.keymetrics.io/)
- a Process Manager for Node. It keeps your processes alive in production, and offers tons of features to manage them and monitor them.
* [rimraf](https://github.com/isaacs/rimraf)
- a neat simple package to delete files with cross platform support.
* [cross-env](https://github.com/kentcdodds/cross-env)
- a small package called to make environment variable syntax work on Windows as well.
* [Webpack](https://webpack.js.org/)
- a module bundler that takes a whole bunch of various source files, processes them, and assembles them into one (usually) JavaScript file called a bundle, which is the only file your client will execute.
* [React](https://facebook.github.io/react/)
- library for building user interfaces by Facebook. It uses the JSX syntax to represent HTML elements and components while leveraging the power of JavaScript.
* [Jest](https://facebook.github.io/jest/)
- a JavaScript testing library by Facebook. It is very simple to set up and provides everything you would need from a testing library right out of the box. It can also test React components.
* [HMR with React Hot Loader](https://gaearon.github.io/react-hot-loader/)
- powerful Webpack feature to replace a module on the fly without reloading the entire page.
* [ImmutableJS](https://facebook.github.io/immutable-js/)
- library by Facebook to manipulate immutable collections, like lists and maps. Any change made on an immutable object returns a new object without mutating the original object.
* [Redux](http://redux.js.org/)
- library to handle the lifecycle of your application. It creates a store, which is the single source of truth of the state of your app at any given time.
* [react-redux](https://github.com/reactjs/react-redux)
- connects a Redux store with React components. With react-redux, when the Redux store changes, React components get automatically updated. They can also fire Redux actions.
* [redux-actions](https://redux-actions.js.org/)
- implements the Flux Standard Action model, which makes action creators return objects with the type and payload attributes.
* [Fetch](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch)
- a standardized JavaScript function to make asynchronous calls inspired by jQuery's AJAX methods.
* [redux-thunk](https://github.com/gaearon/redux-thunk)
- a library that extends Redux's functionality to perform async actions
* [redux-mock-store](https://github.com/arnaudbenard/redux-mock-store)
- a mock store for your testing Redux async action creators and middleware
* [fetch-mock](http://www.wheresrhys.co.uk/fetch-mock/)
- allows mocking http requests made using Fetch
