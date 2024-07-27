## ETH_AVAX_MODULE_2

### Interact with Smart Contract Through a Front-End Application

## Description

In this project, we'll create a simple smart contract with 2-3 functions and display the values of those functions in a front-end application. The files `index.js`, `MySmartContract.sol`, and `deploy.js` will help us practice interacting with our smart contract through a web interface.

## Prerequisites

- Node.js (v14.0.0 or higher)
- MetaMask wallet extension installed in your browser

## Getting Started

After cloning the GitHub repository, follow these steps to get the code running on your computer:

1. Open the project directory in your terminal and run: npm i   
2. Open two additional terminal windows in VS Code.
3. In the second terminal, run: npx hardhat node
4. In the third terminal, run: npx hardhat run --network localhost scripts/deploy.js
5. In the first terminal, start the front end with: npm run dev
6. Open the application in our browser. It will typically be running on:  http://localhost:3000
  

## Setting Up Local Network and Dummy Account in MetaMask

To allow MetaMask to communicate with your local node, set up a local network in MetaMask:

-> Click on (Add a Network)
-> Click on (Add a Network Manually)
-> Give the (Network name - whatever you want)
-> Set the (New RPC URL - http://127.0.0.1:8545/ )
-> Set the (Chain ID - 31337 )
-> Set the (Currency symbol - ETH )
->Now set the MetaMask wallet network to the newly created local network

## Technologies Used

-> React - JavaScript library for building user interfaces
-> Ethereum - Blockchain network for decentralized applications
-> MetaMask - Wallet and gateway to the Ethereum blockchain
-> ethers.js - Library for interacting with Ethereum smart contracts

## Project Structure
The project is organized as follows:

1. contracts/MySmartContract.sol: Contains the Solidity smart contract code.
2. scripts/deploy.js: Script for deploying the smart contract.
3. src/index.js: Entry point for the React front-end application.
4. src/App.js: Main component of the React application.
5. public/index.html: HTML template for the React application.

## Development Workflow

1. Develop the Smart Contract: Write and test your smart contract in the contracts directory.
2. Deploy the Smart Contract: Use Hardhat to deploy the smart contract to a local Ethereum network.
3. Build the Front-End: Create a React front-end to interact with the deployed smart contract.
4. Test the Integration: Ensure the front-end correctly interacts with the smart contract functions.

## Author

Khushi Ranjana  
21BCS9320@cuchd.in

