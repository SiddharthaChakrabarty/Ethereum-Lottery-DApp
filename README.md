# Ethereum Lottery DApp

This is a simple decentralized lottery application built on Ethereum blockchain using Solidity for smart contract development and React for the front-end interface. Users can enter the lottery by sending a certain amount of ether to the contract and the manager of the contract can pick a winner randomly from the list of participants.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Contract Deployment](#contract-deployment)
- [Testing](#testing)
- [Project Structure](#project-structure)
- [Contributing](#contributing)

## Installation

1. Clone the repository to your local machine:

`git clone https://github.com/SiddharthaChakrabarty/ethereum-lottery-dapp.git`


2. Navigate to the project directory:

`cd ethereum-lottery-dapp`


3. Install dependencies for both the front-end (React) and the back-end (Solidity smart contract):

`cd client
npm install
cd ../ethereum
npm install`


## Usage

1. Start the local Ethereum development network (Ganache):

`cd ethereum
npm start`


2. Compile and deploy the smart contract to the local network:

`node deploy.js`


3. Start the front-end React application:

`cd ../client
npm start`


4. Access the application in your browser at `http://localhost:3000`.


## Entering Player into the Lottery

   <img width="771" alt="image" src="https://github.com/SiddharthaChakrabarty/Ethereum-Lottery-DApp/assets/119057806/2cb140ae-57bc-48c7-a9e6-8e8f376a2697">


## Picking winner from the Lottery

   <img width="781" alt="image" src="https://github.com/SiddharthaChakrabarty/Ethereum-Lottery-DApp/assets/119057806/94c56522-5500-4289-b178-227be7a99ec2">



## Contract Deployment

To deploy the smart contract to a live Ethereum network, follow these steps:

1. Replace the `HDWalletProvider` parameters in `deploy.js` with your mnemonic phrase and Infura endpoint.
2. Run the deployment script:

`node deploy.js`


3. The contract address will be logged to the console upon successful deployment.

## Testing

Automated tests are provided for the smart contract using Mocha and Ganache. To run the tests:

`cd ethereum
npm test`


## Project Structure

- **client**: Contains the front-end React application.
  - **public**: Static assets and HTML template.
  - **src**: React components and application logic.
- **ethereum**: Contains the Solidity smart contract and deployment scripts.
- **compile.js**: Script to compile the Solidity contract.
- **deploy.js**: Script to deploy the compiled contract to a network.
- **README.md**: Project documentation.

## Contributing

Contributions are welcome! Please feel free to submit issues, feature requests, or pull requests.


