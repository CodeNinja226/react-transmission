# react-transmission

## Introduction

React Transmission is an ongoing reimplementation of [Transmission](https://transmissionbt.com) web interface.

You can find the original web interface source code [here](https://github.com/transmission/transmission/blob/master/web/)

The official [Transmission repository](https://github.com/transmission/transmission)

## Goals

- **Bump technology used:** More modern frameworks and technologies for a better modularization, performance and correctness.
- **Accelerate development:** With the new set of technologies and components available in this project, new features are easier to implement.
- **Javascript best practices:** Better source modularization, more documentation, source linting and many other improvements.
- **More reliable & accurate behaviour:** Guarantee always that the interface reacts as expected and doesn't face UI race conditions.
- **Tested:** A set of tests to guarantee the everything works as expected.
- **Internationalization:** to be able to translate the interface easialy to other languages.

## Roadmap

- First stage: achieve 100% feature parity with the original web interface.
- Second stage: present this project to the main [Transmission](https://transmissionbt.com) development team to be evaluated
- Third stage: merge this project to the [Transmission repository](https://github.com/transmission/transmission)
- Fourth stage: improve the user interface with new features, more tests, add new languages, etc.

## Technology

- [Webpack](https://webpack.github.io/)
- [React](https://facebook.github.io/react/)
- [Mobx](https://mobxjs.github.io/mobx/)
- [CSS modules](https://github.com/css-modules/css-modules)

## Requirements

- Node 4.5
- Npm 3

## Installation

To be able to build this project, execute:

```bash
git clone https://github.com/fcsonline/react-transmission
cd react-transmission
npm install
npm start
```

Open Transmission daemon and then enable the web interface from the Settings window.

Check this new interface out going to: `http://localhost:3000`

## License

MIT