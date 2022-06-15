# Basic Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, a sample script that deploys that contract, and an example of a task implementation, which simply lists the available accounts.

It also comes with the hardhat deploy folder for the hardhat plugin. 

Try running some of the following tasks:

```shell
npx hardhat accounts
npx hardhat compile
npx hardhat clean
npx hardhat test
npx hardhat node
node scripts/sample-script.js
npx hardhat help
```
How to Verify Smart Contracts with Hardhat Deploy plugin
Refer to this repository if you want extra guidance on project set up.

Hardhat is a development environment to compile, deploy, test, and debug contracts for EVM compatible blockchains.

This tutorial will cover how to use the hardhat-deploy plugin, specifically to verify deployed contracts on the Telos explorer on mainnet.

Setup Hardhat project with the hardhat-deploy plugin
Deploy contracts using the plugin
Verify the contracts on sourcify
Verify contracts using hardhat-deploy plugin
Setup

First, we need to setup our local environment. If you don't already know how to set up a local hardhat project refer to this page to get your environment setup.

Add a deploy folder in primary directory
Past the following code block into the deploy folder under filename - deploy.js
