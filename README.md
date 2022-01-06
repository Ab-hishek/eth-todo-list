# Ethereum Todo List

This is a todo list web-based application powered by Ethereum smart contracts.

# Prerequisites

- [Ganache Personal Blockchain](https://trufflesuite.com/ganache/)
- [Node.js](https://nodejs.org/en/)
- [Truffle Framework](https://trufflesuite.com/)
- [Metamask Etherium Wallet](https://chrome.google.com/webstore/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn?hl=en)

# Instructions to have a working TodoList App

1. `npm install` on root directory of the project
2. Download and open up Ganache (https://www.codeooze.com/blockchain/ethereum-dev-environment-2019/)
3. Compile contaracts using the command `truffle compile` (truffle should be installed globally)
4. In Ganache, create a new workspace and save (make sure the port number is 7545 in the server section)
5. Type command `truffle migrate` to deploy the smart contract onto ganache's local blockchain network
6. Download Metamask extension for your browser and log in to Metamask using the Ganache seed account (12 word mnemonic from Ganache)
7. Change metamask network to localhost 7545
8. Run command `npm run dev` in the root folder
