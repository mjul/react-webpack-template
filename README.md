# Welcome to react-webpack-template
> This repository holds a base template for the new version of generator-react-webpack.
It can be understood as the prototype for newly generated projects.

[![Build Status](https://travis-ci.org/weblogixx/react-webpack-template.svg)](https://travis-ci.org/weblogixx/react-webpack-template)

## Features
The following features are currently included:

- [x] Webpack and Webpack-Dev-Server, including hot-loader
- [x] Babel and JSX
- [x] Mocha Unit tests (*optional*)
- [x] EsLint Support
- [x] No dependency on grunt, gulp or the next hot taskrunner!
- [x] Support for environment-specific configuration files

## Todo
- [ ] Better performance for webpack builds

## What is it for?
This template can be used directly for the creation of new projects. When using it like this, make sure to ___not___ install it via npm but download it directly. The template is (nearly) useless for itself when downloaded via npm!

Basically, it is currently only used as the base template of [generator-react-webpack](https://github.com/newtriks/generator-react-webpack).

## Using it
The template uses webpack as build tool to serve files and run tests. The following commands are available:
```bash
# Start for development
npm start # or
npm run serve

# Start the dev-server with the dist version
npm run serve:dist

# Just build the dist version and copy static files
npm run dist

# Run unit tests
npm test

# Run the unit tests continuously (repeat the test when code changes are saved)
npm run test:watch

# Lint all files in src (also automatically done AFTER tests are run)
npm run lint

# Clean up the dist directory
npm run clean

# Just copy the static assets
npm run copy
```

You can also use your globally installed version of webpack like this:
```bash
# Build or run the dev version:
webpack
webpack --env=dev

webpack-dev-server
webpack-dev-server --env=dev

# Build or run the dist version
webpack --env=dist
webpack-dev-server --env=dist
```

## License
react-webpack-template is available under MIT-License and can therefore be used in any project free of charge.

## Contributors
- Christian Schilling (cs@weblogixx.de)
- Martin Jul (martin@mjul.com)
- Stephan Herzog (sthzgvie@gmail.com)
