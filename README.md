## Work done by:
Souha Ben Hassine, Ahmed Grati, Zeineb Labbane & Nour Belmabrouk

## Setting Up
### 1. Clone/Download the Repository

### 2. Install Dependencies:
```
$ cd Web3TwitterApp
$ npm install
```
### 3. Boot up local development blockchain
```
$ cd Web3TwitterApp
$ npx hardhat node
```

### 4. Connect development blockchain accounts to Metamask
- Copy private key of the addresses and import to Metamask
- Connect your metamask to hardhat blockchain, network 127.0.0.1:8545.
- If you have not added hardhat to the list of networks on your metamask, open up a browser, click the fox icon, then click the top center dropdown button that lists all the available networks then click add networks. A form should pop up. For the "Network Name" field enter "Hardhat". For the "New RPC URL" field enter "http://127.0.0.1:8545". For the chain ID enter "31337". Then click save.  


### 5. Run deploy script to migrate smart contracts
`$ npx hardhat run scripts/deploy.js --network localhost`

### 6. Run Tests
`$ npx hardhat test`

### 7. Launch Frontend
`$ npm run start`

## [Demo](https://github.com/Souha-BH/Web3TwitterApp/blob/main/BlockchainProjectDemo.mov)
## [Report](https://github.com/Souha-BH/Web3TwitterApp/blob/main/RapportBlockchain.pdf)

