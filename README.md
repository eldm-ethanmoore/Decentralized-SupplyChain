# Decentralized-SupplyChain

## Libraries/Versions Used

* truffle - 4.1.14
* web3 - 0.20.6
* Node - 14.17.0
* Ganache-cli - 6.12.2
* @truffle/hdwallet-provider - 1.4.1
* npm - 6.14.13
* chai - 4.3.4
* solidity - 0.4.24
* lite-server - 2.4.0
* webpack - 5.38.1
* webpack-dev-server - 3.11.2

## Library Write Up

I used the Node Package Manager and Node the javascript runtime environment for the SupplyChain Dapp. I also used Truffle development framework and Ganache-cli development environemnt for testing smart contract deployment and interactions. Solidity is the smart contract language utilized. The @truffle/hdwallet-provider library is used to sign transactions. Chai is the testing library for the smart contracts. Web3 is the ethereum javascript api. Lite-server, webpack, and webpack-dev-server are used for running the Dapps front-end locally.

## Contract Address and Transaction Hash

Contract Addr: 0xbD31101D19234D52F1a4e431eD3e8bD1D521a2E0

Transaction Hash: 0xf37cfaac9c2e7d66605eab5919637bbb5c081ed8b2e63be78582a87071a674bd

## UML Diagrams

### Activity Diagram

![Activity Diagram](https://github.com/eldm-ethanmoore/Decentralized-SupplyChain/blob/main/Diagrams/ActivityDiagram.PNG)

### Sequence Diagram

![Sequence Diagram](https://github.com/eldm-ethanmoore/Decentralized-SupplyChain/blob/main/Diagrams/SequenceDiagram.PNG)

### State Diagram

![State Diagram](https://github.com/eldm-ethanmoore/Decentralized-SupplyChain/blob/main/Diagrams/StateDiagram.PNG)

### Data Model Diagram

![Data Model Diagram](https://github.com/eldm-ethanmoore/Decentralized-SupplyChain/blob/main/Diagrams/DataModelDiagram.PNG)

# Supply chain & data auditing

This repository contains an Ethereum DApp that demonstrates a Supply Chain flow between a Seller and Buyer. The user story is similar to any commonly used supply chain process. A Seller can add items to the inventory system stored in the blockchain. A Buyer can purchase such items from the inventory system. Additionally a Seller can mark an item as Shipped, and similarly a Buyer can mark an item as Received.

The DApp User Interface when running should look like...

![truffle test](images/ftc_product_overview.png)

![truffle test](images/ftc_farm_details.png)

![truffle test](images/ftc_product_details.png)

![truffle test](images/ftc_transaction_history.png)


## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

Please make sure you've already installed ganache-cli, Truffle and enabled MetaMask extension in your browser.

```
Give examples (to be clarified)
```

### Installing

> The starter code is written for **Solidity v0.4.24**. At the time of writing, the current Truffle v5 comes with Solidity v0.5 that requires function *mutability* and *visibility* to be specified (please refer to Solidity [documentation](https://docs.soliditylang.org/en/v0.5.0/050-breaking-changes.html) for more details). To use this starter code, please run `npm i -g truffle@4.1.14` to install Truffle v4 with Solidity v0.4.24. 

A step by step series of examples that tell you have to get a development env running

Clone this repository:

```
git clone https://github.com/udacity/nd1309/tree/master/course-5/project-6
```

Change directory to ```project-6``` folder and install all requisite npm packages (as listed in ```package.json```):

```
cd project-6
npm install
```

Launch Ganache:

```
ganache-cli -m "spirit supply whale amount human item harsh scare congress discover talent hamster"
```

Your terminal should look something like this:

![truffle test](images/ganache-cli.png)

In a separate terminal window, Compile smart contracts:

```
truffle compile
```

Your terminal should look something like this:

![truffle test](images/truffle_compile.png)

This will create the smart contract artifacts in folder ```build\contracts```.

Migrate smart contracts to the locally running blockchain, ganache-cli:

```
truffle migrate
```

Your terminal should look something like this:

![truffle test](images/truffle_migrate.png)

Test smart contracts:

```
truffle test
```

All 10 tests should pass.

![truffle test](images/truffle_test.png)

In a separate terminal window, launch the DApp:

```
npm run dev
```

## Built With

* [Ethereum](https://www.ethereum.org/) - Ethereum is a decentralized platform that runs smart contracts
* [Truffle Framework](http://truffleframework.com/) - Truffle is the most popular development framework for Ethereum with a mission to make your life a whole lot easier.


## Authors

See also the list of [contributors](https://github.com/your/project/contributors.md) who participated in this project.

## Acknowledgments

* Solidity
* Ganache-cli
* Truffle

## Contact Me!
Author: Ethan Moore  
Email: eldm2350@protonmail.com  
Github: https://github.com/eldm-ethanmoore  
LinkedIn: https://www.linkedin.com/in/ethan-moore-a7106121a/  
Website: https://eldm.net
