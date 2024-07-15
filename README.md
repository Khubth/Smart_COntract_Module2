# Smart_COntract_Module2
 
 #  Smart Contract (MySmartContract.sol)
> Functions: Create a simple smart contract with 2-3 functions.

> getData(): Returns some data stored in the contract.
> setData(string newData): Sets new data in the contract.

 # Description:
  Develop a React application to interact with the smart contract.

 1. index.js: Entry point for the React application.
 2. MySmartContract.sol: Solidity file defining the smart contract.
 3. deploy.js: Script to deploy the smart contract.
 4. scripts/ directory: Contains deployment script (deploy.js).
 
# Requirements:

 1. Node.js (v14.0.0 or higher) installed.
 2. MetaMask wallet extension installed in your browser.
 3. Starter Next.js or Hardhat project setup.

# Deployment and Setup
 
 Steps:
 1. Install project dependencies: npm install
 2. Start a local Ethereum node using Hardhat: npx hardhat node
 3. Deploy your smart contract to the local network:

   npx hardhat run --network localhost scripts/deploy.js

 4. Start the React application: npm run dev

# Configuring MetaMask:

1. Open MetaMask and add a custom network:
2. Network Name: ETH (As per your choice)
3. New RPC URL: http://127.0.0.1:8545/
4. Chain ID: 31337
5. Currency Symbol: ETH
6. Switch MetaMask to use the newly added local network.

# Technologies Used

1. React: JavaScript library for building user interfaces.
2. Ethereum: Blockchain network for decentralized applications.
3. MetaMask: Ethereum wallet and gateway to blockchain networks.
4. ethers.js: JavaScript library for interacting with Ethereum smart contracts.

# Author
Khushi Ranjana

