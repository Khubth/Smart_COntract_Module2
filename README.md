# Smart_COntract_Module2
 
 #  Smart Contract (MySmartContract.sol)
> Functions: Create a simple smart contract with 2-3 functions.

> getData(): Returns some data stored in the contract.
> setData(string newData): Sets new data in the contract.

 # Description:
  Develop a React application to interact with the smart contract.

 > index.js: Entry point for the React application.
 > MySmartContract.sol: Solidity file defining the smart contract.
 > deploy.js: Script to deploy the smart contract.
 > scripts/ directory: Contains deployment script (deploy.js).
 
# Requirements:

 > Node.js (v14.0.0 or higher) installed.
 > MetaMask wallet extension installed in your browser.
 > Starter Next.js or Hardhat project setup.

# Deployment and Setup
 
 Steps:
 > Install project dependencies: npm install
 > Start a local Ethereum node using Hardhat: npx hardhat node
 > Deploy your smart contract to the local network:

   npx hardhat run --network localhost scripts/deploy.js

 > Start the React application: npm run dev

# Configuring MetaMask:

> Open MetaMask and add a custom network:
> Network Name: ETH (As per your choice)
> New RPC URL: http://127.0.0.1:8545/
> Chain ID: 31337
> Currency Symbol: ETH
> Switch MetaMask to use the newly added local network.

# Technologies Used

> React: JavaScript library for building user interfaces.
> Ethereum: Blockchain network for decentralized applications.
> MetaMask: Ethereum wallet and gateway to blockchain networks.
> ethers.js: JavaScript library for interacting with Ethereum smart contracts.

# Author
Khushi Ranjana

