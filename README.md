# Tokenization

## Getting Started

```
npm install -g truffle
truffle unbox react
```

Using the ERC20 Smart Contract from OpenZeppelin, install open-zeppelin v3 with Solidity 0.6 smart contracts:

```
npm install --save @openzeppelin/contracts@v3.0.0
```

## Running Migrations

- Run the truffle developer console:

```
truffle console --network development

migrate
```

- Send 1 ether by typing this in truffle developer console and replace the address

```
web3.eth.sendTransaction({from: accounts[0], to:"USE ADDRESS HERE", value: web3.utils.toWei("1","ether")})
```

- Add in a Central Configuration with DotEnv

```
npm install --save dotenv
```

## Add KYC, or "know your customer"

![image of app](https://github.com/miriamdong/Tokenization/blob/master/Doc/screencapture-localhost-3000-2021-05-11-00_02_27.png?raw=true)
Whitelisting and give someone permission to do something.

## Frontend: Load Contracts to React

```
cd client && npm run start
```

## Deploy Smart Contracts With MetaMask

Add HDWalletProvider and the Mnemonic to Truffle and modify truffle-config.js

```
npm install --save @truffle/hdwallet-provider
```

![image of MetaMask](https://github.com/miriamdong/Tokenization/blob/master/Doc/Screen%20Shot%202021-05-11%20at%2012.28.38%20AM.png?raw=true)

## Real-World Use-Case for this Project

💰 Tokenization of any Assets as fungible Tokens (ERC20)

🏦 Creation of Bonus Programs, Vouchers, etc.

💲 Creation of a new crypto currency

🧾 Creation of a Payment-layer on top of Ethereum

## Development-Goal

🧰 Understand truffle-config json file

🤖 Understand deployment of dApps

🦸‍♂️ Understand Tokenization using Open-Zeppelin Smart Contracts

## Unit-Testing with Chai

Install Chai

```
npm install --save chai chai-bn chai-as-promised
truffle test
```

### To Deploy on Ganache

```
truffle migrate --network ganache_local
```

### To Deploy on Ropsten Test Network

```
truffle migrate --network ropsten_infura
```
