## ETH_AVAX_MODULE_2

### Interact with Smart Contract Through a Front-End Application

## Description

In this project, we'll create a simple smart contract with 2-3 functions and display the values of those functions in a front-end application. The files `index.js`, `MySmartContract.sol`, and `deploy.js` will help us practice interacting with our smart contract through a web interface.

## Prerequisites

- Node.js (v14.0.0 or higher)
- MetaMask wallet extension installed in your browser

## Getting Started

After cloning the GitHub repository, follow these steps to get the code running on your computer:

1. Open the project directory in your terminal and run: 
   
    npm i
    
2. Open two additional terminal windows in VS Code.
3. In the second terminal, run:
   
    npx hardhat node

4. In the third terminal, run:
  
    npx hardhat run --network localhost scripts/deploy.js
 
5. In the first terminal, start the front end with:

    npm run dev


6. Open the application in our browser. It will typically be running on:

    http://localhost:3000
  

## Setting Up Local Network and Dummy Account in MetaMask

To allow MetaMask to communicate with your local node, set up a local network in MetaMask:

1. Click on the MetaMask extension and then on the network selection button (top middle button).
2. Click "Add a Network" and then "Add a Network Manually."
3. Fill in the following details:
   - Network Name: (any name you want)
   - New RPC URL: `http://127.0.0.1:8545/`
   - Chain ID: `31337`
   - Currency Symbol: `ETH`
4. Set your MetaMask wallet network to the newly created local network.

## Technologies Used

- React - JavaScript library for building user interfaces
- Ethereum - Blockchain network for decentralized applications
- MetaMask - Wallet and gateway to the Ethereum blockchain
- ethers.js - Library for interacting with Ethereum smart contracts

## Author

Khushi Ranjana  
21BCS9320@cuchd.in

