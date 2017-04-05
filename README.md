

## Included Technologies & Libraries
- [Angular +2.x](http://angular.io) 
- Bootstrap v3.x (SASS)
- Typescript 2.x
- ES6 / ES2015 (using Loader Spec)
- Webpack 2.x

### Quick start
**Make sure you have Node version >= 5.0 and NPM >= 3**

```bash
# install the repo with npm
npm install

# start the server
npm start

# use Hot Module Replacement (disabled for now)
# npm run server:dev:hmr
```
go to [http://0.0.0.0:3000](http://0.0.0.0:3000) or [http://localhost:3000](http://localhost:3000) in your browser

File Stracture :

angular2-webpack-starter/
 ├──config/                    * configuration
 |   ├──helpers.js             * helper functions for our configuration files
 |   ├──spec-bundle.js         * angular 2 testing environment
 |   ├──karma.conf.js          * karma config for our unit tests
 |   ├──protractor.conf.js     * protractor config for our end-to-end tests
 │   ├──webpack.dev.js         * development webpack config
 │   ├──webpack.prod.js        * production webpack config
 │   └──webpack.test.js        * testing webpack config
 │
 ├──src/                       * source files that will be compiled to javascript
 |   ├──main.browser.ts        * entry file for our browser environment
 │   │
 |   ├──index.html             * Index.html: where we generate index page
 │   │
 |   ├──polyfills.ts           * polyfills file
 │   │
 |   ├──vendor.ts              * vendor file
 │   │
 │   ├──app/                   * WebApp: folder
 │   │   ├──app.spec.ts        * a simple test of components in app.ts
 │   │   ├──app.e2e.ts         * a simple end-to-end test for /
 │   │   └──app.ts             * App.ts: a simple version of our App component components
 │   │
 │   └──assets/                * static assets are served here
 │       ├──icon/              * list of icons from www.favicon-generator.org
 │       |──service-worker.js  * Please ignore this. Web App service worker that's not complete yet
 │      
 │
 │
 ├──tslint.json                * typescript lint config
 ├──typedoc.json               * typescript documentation generator
 ├──tsconfig.json              * config that webpack uses for typescript
 ├──package.json               * what npm uses to manage it's dependencies
 └──webpack.config.js          * webpack main configuration file

