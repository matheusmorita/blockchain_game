# blockchain-game

![memory](https://cdn.discordapp.com/attachments/811040342811476049/936856198781759488/unknown.png)

(This is a preview of the game working)

##

# About

This is a personal project of a web 3.0 game deployed in a blockchain, feel free to contribute. 

# Tools

 - [solidity 0.8](https://docs.soliditylang.org/en/v0.8.11/)
 - [javascript](https://www.javascript.com/)
 - [web3.js](https://web3js.readthedocs.io/en/v1.7.0/)
 - [ReactJS](https://reactjs.org/)
 - [CSS]
 - [Truffle](https://trufflesuite.com/)
 - [Ganache](https://trufflesuite.com/ganache/)

# Steps

 - Initialize your ganache, to have a blockchain and wallets to test your smartcontract locally
 - You can test the smartcontract functions before deploying using:

```bash
truffle test
```
 - Deploy the contract using 

```bash
truffle migrate
```

 - Initialize the front-end application to play the game

```bash
npm run start
```

 - Configure your metamask to access localhost network
```bash
Settings > Networks, if you dont see a localhost network, add a network with these parameters:
 - Network Name: HTTP://127.0.0.1:7545 
 - New RPC URL: HTTP://127.0.0.1:7545
 - Chain ID: 5777
 - Currency Symbol: ETH
 ```
 
 # How it works
 
 You have a memory game, so in this case, if you fid the same image you can mint a NFT to your wallet and sell wherever you want.
