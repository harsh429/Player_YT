

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

-## File Structure (adopted from angularclass)
 -I use the component approach in our starter. This is the new standard for developing Angular apps and a great way to ensure maintainable code by encapsulation of our behavior logic. A component is basically a self contained app usually in a single file or a folder with each concern as a file: style, template, specs, e2e, and component class. Here's how it looks:
 -```
 -angular2-webpack-starter/
 - ├──config/                    * configuration
 - |   ├──helpers.js             * helper functions for our configuration files
 - |   ├──spec-bundle.js         * ignore this magic that sets up our angular 2 testing environment
 - |   ├──karma.conf.js          * karma config for our unit tests
 - |   ├──protractor.conf.js     * protractor config for our end-to-end tests
 - │   ├──webpack.dev.js         * development webpack config
 - │   ├──webpack.prod.js        * production webpack config
 - │   └──webpack.test.js        * testing webpack config
 - │
 - ├──src/                       * source files that will be compiled to javascript
 - |   ├──main.browser.ts        * entry file for our browser environment
 - │   │
 - |   ├──index.html             * Index.html: where we generate our index page
 - │   │
 - |   ├──polyfills.ts           * our polyfills file
 - │   │
 - |   ├──vendor.ts              * our vendor file
 - │   │
 - │   ├──app/                   * WebApp: folder
 - │   │   ├──app.spec.ts        * a simple test of components in app.ts
 - │   │   ├──app.e2e.ts         * a simple end-to-end test for /
 - │   │   └──app.ts             * App.ts: a simple version of our App component components
 - │   │
 - │   └──assets/                * static assets are served here
 - │       ├──icon/              * our list of icons from www.favicon-generator.org
 - │       ├──service-worker.js  * ignore this. Web App service worker that's not complete yet
 - │
 - │
 - ├──tslint.json                * typescript lint config
 - ├──typedoc.json               * typescript documentation generator
 - ├──tsconfig.json              * config that webpack uses for typescript
 - ├──package.json               * what npm uses to manage it's dependencies
 - └──webpack.config.js          * webpack main configuration file
-
 -```
 -

 

