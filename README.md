```
	start application:
	> npm install
	> npm start
	> browse to http://localhost:8080/

	run tests:
	> npm run test or test:watch
```

This is SPA implementation of the Hacker News website. Was originally planning to use Redux but then it didn't seem necessary. Users
can choose between six of the stories provided by the HN API. Application runs off of a webpack-dev server as all XMLHttpRequests are done
client side.

Libraries/Modules:
* React
* Bootstrap
* moment.js
* react-paginate
* react-scroll

Dev Libraries:
* Babel
* Webpack
* Mocha / Chai / Sinon / nock / Enzyme
