### 0.1.1

- Fix crash when updating peripheral state at 2nd time.
- Rename npm scripts
  - `npm run local`, run sensor-web3 by loading peripheral-service from `./lib/index.js` that wraps `./lib/bundle.min.js` built by browserify and uglify-es
  - `npm run src`, run sensor-web3 by loading peripheral-service from `./src/index.js`
- Improve logging by updating `start-yapps-docker` to mount current plugin directory to `/opt/plugins` in Docker image (it was mounted at `/opt` in previous version).

### 0.1.0

- Add npm scripts for building ES6 javascript sources into single bundle source.
  - `npm run build`, use browserify/uglify-es to build javascript bundle
  - `npm run deploy`, run sensor-web3 by loading peripheral-service from `./lib/index.js` that wraps `./lib/bundle.min.js` built by browserify and uglify-es
  - `npm run src`, run sensor-web3 by loading peripheral-service from `./src/index.js`

### 0.0.3

- Apply `use strict` for all javascript sources.

### 0.0.2

- Apply ES6/OOP for cpu and memory monitors.

### 0.0.1

- Initial version