# Technical Task: Front End Web Developer

We want to see you create a simple block explorer for the Cosmos Hub blockchain using a reactive front-end framework like Vue.js or React. Included in this repository is some Vue boilerplate to get your started. You can use React if you prefer, but we don't have boilerplate ready for you.

## Specification

Here are the specifications about what the explorer should be able to do:

* The GUI should be responsive and work well for recent versions of mobile and PC web browsers.
* The Home view should show a list of the most recently generated 10 blocks, as well as when they were generated.
* The Home view should have an interactive form that lets the user input a number and search for a particular block. If the block exists, it should redirect them to a block details view.
* There should be a Block view that let users view the information for a specific block
* We would like this block explorer to contain unit tests.

Can you help us build this web application? Feel free to use the frontend framework of your choice. We are not grading you on visual look and feel, only the technical implementation, usability, and accessibility.

We don't want you to have to stay up all night working on this app. The task should take no more than 8 hours. If you are stuck on something, feel free to reach out for help or clarification.

## Resources

You have these official JSON-RPC endpoints at your disposal that contain the live state data for the Cosmos Hub mainnet. Please use them in your application to show blockchain state.

* [Tendermint RPC Endpoint](https://rpc.nylira.net)
* [Tendermint RPC Docs](https://tendermint.com/rpc)

* [Cosmos REST Endpoint](https://lcd.nylira.net)
* [Cosmos REST Docs](https://cosmos.network/rpc)

## Example Blockchain Explorers

Here are some fully fleshed out block explorers you can take inspiration from:

* [Cosmos Overview](https://cosmos-overview.genesislab.net)
* [Hubble](https://hubble.figment.network)
* [Cosmos Visualizer](https://nylira.net/3d)
* [Stargazer](https://stargazer.certus.one)

## Project setup
```
yarn
```

### Compiles and hot-reloads for development
```
yarn serve
```

### Compiles and minifies for production
```
yarn build
```

### Run your tests
```
yarn test
```

### Lints and fixes files
```
yarn lint
```

### Run your end-to-end tests
```
yarn test:e2e
```

### Run your unit tests
```
yarn test:unit
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
