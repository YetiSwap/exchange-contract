# YetiSwap Smart Contracts
This repo contains all of the smart contracts used to run [YetiSwap](yetiswap.app).

## Deployed Contracts
Factory address: [0x58C8CD291Fa36130119E6dEb9E520fbb6AcA1c3a](https://cchain.explorer.avax.network/address/0x58C8CD291Fa36130119E6dEb9E520fbb6AcA1c3a)

Router address: [0x262DcFB36766C88E6A7a2953c16F8defc40c378A](https://cchain.explorer.avax.network/address/0x262DcFB36766C88E6A7a2953c16F8defc40c378A)

## Running
These contracts are compiled and deployed using [Hardhat](https://hardhat.org/). They can also be run using the Remix IDE. A tutorial for using Remix is located [here](https://docs.avax.network/build/tutorials/platform/deploy-a-smart-contract-on-avalanche-using-remix-and-metamask).

To prepare the dev environment, run `yarn install`. To compile the contracts, run `yarn compile`. Yarn is available to install [here](https://classic.yarnpkg.com/en/docs/install/#debian-stable) if you need it.

## Accessing the ABI
If you need to use any of the contract ABIs, you can install this repo as an npm package with `npm install --dev @yetiswap/exchange-contracts`. Then import the ABI like so: `import { abi as IYetiSwapPairABI } from '@yetiswap/exchange-contracts/artifacts/contracts/yetiswap-core/interfaces/IYetiSwapPair.sol/IYetiSwapPair.json'`.

## Attribution
These contracts were adapted from these Uniswap repos: [uniswap-v2-core](https://github.com/Uniswap/uniswap-v2-core), [uniswap-v2-periphery](https://github.com/Uniswap/uniswap-v2-core), and [uniswap-lib](https://github.com/Uniswap/uniswap-lib).
