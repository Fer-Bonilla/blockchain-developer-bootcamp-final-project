# :star2: Miluka

Welcome to Miluka, the Dapp to create micro lotteries that let the people win instant prizes that can cash using the token platform. The Dapp first version planned for the Consensys Bootcamp includes the micro-lotteries creation, users registration, and betting and prize withdrawal to the winner Ethereum Address.

## :iphone: The Dapp

1) Users can bet into a micro-lottery from three different sizes(Defined by top value) with a fixed betting value of numbers of lottery tokens for each one.

2) If there is a previous lottery with the same top limit opened with slots available, the user is assigned to this one

3) Users are assigned to open lotteries until a top value is achieved, and then the smart contract executes an oracle call to get the winner's address, and prize withdrawal is executed to the lottery winner instantly.

4) Users can select a percentage of prize for automatic betting on new micro-lotteries with a user rule defined and withdrawal condition defined.

5) Lottery token can be a swap for a contract base stable-coin token in the local currency (Currency from the country where the user is registered) and business partners can offer products to buy directly from the platform.

6) Bussiness partner e-commerce platform can offer discounts and products. A business partner can take liquidity from the stable-coin wallet or use it with other partners to improve cash management through the platform.

## :four_leaf_clover: Micro lottery types

![image](https://github.com/Fer-Bonilla/blockchain-developer-bootcamp-final-project/blob/main/milukapng.png)

## Dapp diagram

### Activy diagram



### Sequence diagram



### State diagram


### Class Diagram


## 👩🏻‍💻 The contract roles

1. Players
2. Patners
3. Contract Owner

### 📜 The Rules

1) Lottery Pools are short time and fast closing bets. If the top value of the lottery is not achieved at a specified time, the micro lottery is canceled and funds are sent back to the owners.

2) Prizes are paid instantly after the contract oracle is confirmed

3) Automatic betting is defined by the user in his own wallet and executed until defines rules are still valid.

4) User can change anytime the betting configuration


### 📖 How to Play

1) Create your account on the Dapp website
2) Users need to accept site and service conditions
3) Users can deposit lottery tokens swapped on any exchange where the token is listed.
4) Select the micro-lottery to bet
5) Configure automatic betting options and withdrawal conditions

## 🛠 Technology

- Ethereum smart contract written in Solidity
- Web from Dapp implemented with react an javascript
- Tools and libraries used: Truffle, Openzeppelin, NodeJS, Bootstrap
- Chainlink oracles

## 🚀‍ Development

### Prerequisites
- Node v10.5.0
- Solidity v0.9.0
- Chainlink
- Truffle v5.0.7

### Setup
- Clone the git repo  
- Have a local blockchain running on port 8545 (e.g. using [Ganache](https://www.trufflesuite.com/ganache))
- Run `npm install`
- Run `npm run dev`
- Open up your browser and the project should be up on localhost:3000

### Contract interaction on a local blockchain
- Ensure your browser has a plugin (e.g. [Metamask](https://metamask.io/)) that allows you to interact with the Ethereum blockchain
- Ensure you have a local blockchain running (e.g. on Ganache)
- Select *Localhost:8545* or *Custom RPC* depending on which port your Ganache blockchain is running on
- Interact with the web interface

## ✅ Testing
- You can run the tests by running `truffle test` from the Dapp main directory
