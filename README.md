# decentralized-game-template

<!-- [![Open in Gitpod!](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/alto-io/decentralized-game-template) -->

Installation
====

<!-- If you are using Gitpod, you can skip this section! Your environment is already set up 🎉 -->

  * Make sure you have Node.js ≥ 12 installed (https://nodejs.org)
  * Install dependencies: `npm install`

Running The Example Game
==============

The repo includes the example Breakout game from Phaser 3.0 in the /docs folder.

* `npm start`: Run the game locally

Deployment 
================

### Deploying on Github Pages

Since the game is in the docs folder it can easily be deployed via the <a href="../../settings/pages">Github Pages Settings Page</a>.

### Deploying on IPFS

To deploy on IPFS we need to do the following steps:

* Retrieve API keys from [Pinata](https://pinata.cloud/)

  * PINATA_API_KEY
  * PINATA_API_SECRET_KEY

* Input these keys as <a href="../../settings/secrets/actions">Repository Secrets</a>

* Go to the <a href="../../actions/workflows/release.yaml">Release Workflow</a> on Github Actions and click `Run Workflow`

<!--

### Using A DNS




Using The Web 3 Wallet
========

-->