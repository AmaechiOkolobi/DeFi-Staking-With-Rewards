# "Decentralised Exchange Liquidity Pool Staking & Rewards"
### Built with Solidity, Javscript, Hardhat, Ethers, Chai, Openzeppelin

## Description

This repository is a project I developed to provide passive income for users by staking tokens. In future I intend to add a suite of gambling smart contracts to provide a use case for the rewards.

The main aspect to notice in this repository is my use of Hardhat forking feature when writing my tests. This allowed me to fork the state of the mainnet in order to properly test the JoeRouter exchange's interaction with my Solidity smart contracts. You can see evidence of this in test/liquidity.js and test/peachNode.js

This project shows my ability to interact with existing DeFi exchange platforms, in this case I used TraderJoe which is an Avalanche Fork of Uniswap.

## How To Run
 1. Clone Repository
 2. Install Dependencies:
 $ npm install
 3. Deploy Contracts
 $ npx hardhat run --network NETWORK_NAME scripts/deploy.js