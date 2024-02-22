# Decentralized-Voting-Application

## dApp implementing Blockchain

## Live Project - https://voting-dapp235.netlify.app/

## Project Files - https://github.com/Pragna235/Decentralized-Voting-Application/tree/master

## Playbook

### Technologies used
 - `Solidity` - To write a smart contract
 - Any ethereum based blockchain (in this project, `Sepolia` testnet is used)
 - Application runs in `React.js` and it communicates with the blockchain through `hardhat ether.js` framework
 - `Metamask` extension to connect to the blockchain addresses to communicate with the smart contract
 - Application runs on the `client-side` of the browser

## Basic Integration Template

https://github.com/Pragna235/Decentralized-Voting-Application/tree/main (Files)

- Create a new folder `Voting dApp` and add a `package.json` with the required dependencies
-     npm install
- Create a `.env` file and add your `API_KEY` and `PRIVATE_KEY` variables
-     npx hardhat
- Add your `Voting.sol` smart contract to the `contract` folder
- Make changes in the `deploy.js` file
-     npx hardhat compile
- Make changes in the `hardhat.config.js`
-     npx hardhat run --network sepolia scripts/deploy.js
- Paste the obtained smart contract address in `CONTRACT_ADDRESS` variable of the `.env` file


- Go to `cmd`
-     npx create-react-app react-voting-app .`
- Navigate to the React app folder
-     cd react-voting-app
- Initiate the VSCode of this folder
-     code .
- Make changes in the `App.js` by removing the header tag and the logo
- Make changes in the code of the folders as required
-     npm install ethers@5.7.1
- Make all necessary changes in the code and run 'em

## Deploy on netlify.com
- Navigate to the react-app folder
-     npm run build
- Upload the `build` folder manually on `netlify.com`
- Change the domain name and voila...
