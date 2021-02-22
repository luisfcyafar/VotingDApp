# Voting decentralized app mock

This Project is a quickstart taking aproach of the truffle boxes to build your own dapp with truffle suite and metamask.


### Tech
This project was made using:

* Truffle - To migrate and test solidity contracts
* pet Shop truffle box - As a quickstart truffle app
* Ganache - As RPC
* Metamask - As Ethereum bridge
* web3 - Ethereum js api
* Solidity - To write smart contracts
* Javascript - To render and handle front end data

### Installation

this dapp requires you to have installed ganache, truffle, metamask web extension and nodejs + npm to run.

Install the dependencies and devDependencies

```sh
$ npm install
```

Migrate contracts

```sh
$ truffle migrate
```
Start the server
```sh
$ npm run dev
```
Then go to ganache, select an account, copy their private key and go to localhost:3000 ,connect metamask to your rpc server and import the account you have copied.


### Test
In order to test, you can use mocha and chai wich it comes with truffle, using
```sh
$ truffle test
```
