React App Advanced Boilerplate
=====================

React project template with advanced Webpack setup.

### Objective

While the original Pro React book [App Boilerplate](https://github.com/pro-react/react-app-boilerplate) is purposefully simple to show the minimal setup needed to create React projects with Webpack and Babel, this is a more complete setup. It is based on the Appendix A (entirelly dedicated to Webpack) and features JavaScript and CSS bundling, Hot Module Replacement, automatic HTML generation and a separate production configuration with optimization and caching.

### Usage
**Clone this repository**
```
git clone git@github.com:pro-react/react-app-advanced-boilerplate.git
```

**Install**
```
npm install
```

**Start the application in development mode**
```
npm start
```

Open http://localhost:8080 in your browser.

Static files are served from the `public` folder, project JavaScript files are bundled from the `app` folder.

**When ready, build for production**
```
npm run build
```

This will generate a minimized bundle.js file on the `build` folder.
