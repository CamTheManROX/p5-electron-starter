# p5/Electron Starter

**Clone and run for a quick way to use P5js in Electron.**

This quick start template allows you to quickly begin building P5js sketches in Electron. In addition to P5 and Electron, it comes pre-configured with:
- Mocha as the Node.js test suite.
- Electron-reload to keep the sketch up-to-date as you make changes.

In order to keep P5 out of the global scope, it is instantiated inside sketch.js. This means that whenever you would call a p5 method, you must call it from the injected p5 instance. For example, in the sketch function, you must use `p.ellipse()` rather than just `ellipse`.

## To Use

To clone and run this repository you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. From your command line:

```bash
# Clone this repository
git clone https://github.com/electron/electron-quick-start
# Go into the repository
cd p5-electron-quick-start
# Install dependencies
npm install
# Run the app
npm start
```

## To Test
This quick start template employs [MochaJS](https://mochajs.org) as the test framework. To run tests inside the `test` folder from your command line:

```bash
# Install dependencies
npm install
# Run the tests
npm test
```
