# Vite-react-ts-hardhat-web3-NFT tutorial

<p>building a Web3 NFT Minting Dapp with React, TS, Vite, Vitest, Hardhat</p>

## Requirements

- [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

- You'll know you did it right if you can run `git --version` and you see a response like `git version x.x.x`

- [Nodejs](https://nodejs.org/en/)

- You'll know you've installed nodejs right if you can run:

- `node --version`and get an ouput like: `vx.x.x`

- [Yarn](https://classic.yarnpkg.com/lang/en/docs/install/) instead of `npm`

- You'll know you've installed yarn right if you can run:

- `yarn --version` And get an output like: `x.x.x`

- You might need to install it with npm

> If you're familiar with `npx` and `npm` instead of `yarn`, you can use `npx` for execution and `npm` for installing dependencies.

## Quickstart

1. Clone and install dependencies

After installing all the requirements, run the following:

```bash

git clone https://github.com/crisanlucid/vite-react-ts-hardhat-web3-NFT-tutorial/

cd vite-react-ts-hardhat-web3-NFT-tutorial

```

Next:

```

yarn install

```

or

```

npm i

```

2. You can now test the contracts!

```

yarn hardhat test
```

or

```

yarn hardhat test
```

# Usage

If you run `yarn hardhat --help` you'll get an output of all the tasks you can run.

## Deploying Contracts

```

yarn hardhat deploy

```

This will deploy your contracts to a local network. Additionally, if on a local network, it will deploy mock Chainlink contracts for you to interact with. If you'd like to interact with your deployed contracts, skip down to [Interacting with Deployed Contracts](#interacting-with-deployed-contracts).

## Run a Local Network

One of the best ways to test and interact with smart contracts is with a local network. To run a local network with all your contracts in it, run the following:

```

yarn hardhat node

```

You'll get a local blockchain, private keys, contracts deployed (from the `deploy` folder scripts), and an endpoint to potentially add to an EVM wallet.

# Performance optimizations

For faster runs of your tests and scripts, consider skipping ts-node's type checking by setting the environment variable `TS_NODE_TRANSPILE_ONLY` to `1` in hardhat's environment. For more details see [the documentation](https://hardhat.org/guides/typescript.html#performance-optimizations).

# Resources:

https://rahulsethuram.medium.com/the-new-solidity-dev-stack-buidler-ethers-waffle-typescript-tutorial-f07917de48ae

```

```
