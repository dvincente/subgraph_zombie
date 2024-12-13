# Subgraph Project for CryptoZombie

Try running some of the following tasks:

Install Graph CLI using NPM and Initialize your Subgraph.

```shell
npm install -g @graphprotocol/graph-cli
graph init demo-1
```

Authenticate within the CLI, build and deploy your Subgraph to the Studio.

```shell
graph auth *********************
cd demo-1
graph codegen && graph build
graph deploy demo-1
```