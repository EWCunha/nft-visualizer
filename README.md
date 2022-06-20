# Simple NFT visualizer

This app is an NFT visualizer for ERC1155 tokens. To run and check it out, do the following steps:
1. On root folder, run `npm install`;
2. Create a `.env` file and insert a wallet private key (`PRIVATE_KEY`) and a RPC provider (`MUMBAI_RPC`) - recommended: Mumbai testnet (https://rpc-mumbai.maticvigil.com/). **OR** Simply replace this variables on `hardhat.config.js` file;
3. Get some fake MATIC to deploy the smart contract with [this faucet](https://faucet.polygon.technology/);
4. On root folder, run this command on terminal: `npx hardhat run scripts/deploy.js --network mumbai`;
5. Store the address of deployment;
6. Go to the `frontend` folder and run on terminal: `npm install`;
7. Then, run `npm start`;
8. Have fun!
