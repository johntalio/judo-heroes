# judo-heroes

A Universal JavaScript application that uses Node.js as runtime on the backend and React.js and Express on the frontend.
Also uses Babel, Webpack, and EcmaScript 2015 syntax to build code for the browser.

Use this bash script to generate the bundle file: NODE_ENV=production node_modules/.bin/webpack -p
Site can be run using the module http-server using this bash script: node_modules/.bin/http-server src/static
Production code running on a server.js script; runs on JSX syntax, so babel-node command is necessary: NODE_ENV=production node_modules/.bin/babel-node --presets react,es2015 src/server.js
