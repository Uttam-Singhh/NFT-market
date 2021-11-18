# NFT-market
A Metaverse Marketplace in which a user puts an item for sale, the ownership of the item will be transferred from the creator to the marketplace. When a user purchases an item, the purchase price will be transferred from the buyer to the seller and the item will be transferred from the marketplace to the buyer.

The marketplace owner will be able to set a listing fee. This fee will be taken from the seller and transferred to the contract owner upon completion of any sale, enabling the owner of the marketplace to earn recurring revenue from any sale transacted in the marketplace.

![1](https://user-images.githubusercontent.com/63050765/142380348-6be15c90-2138-4846-a225-02a355c1b045.png)
![2](https://user-images.githubusercontent.com/63050765/142380419-346ed6be-a89b-49bd-847a-b52e9d1e8506.jpg)



## Tools, Languages & Frameworks used ⚡️
* Solidity, javascript
* Next.js
* Hardhat
* Ethers.js
* IPFS

## Running this project ☘️

To run this project locally, follow these steps.

1. Clone the project locally, change into the directory, and install the dependencies:

```sh
git clone https://github.com/Uttam-Singhh/NFT-market

# install using NPM or Yarn
npm install

# or

yarn
```

2. Start the local Hardhat node

```sh
npx hardhat node
```

3. With the network running, deploy the contracts to the local network in a separate terminal window

```sh
npx hardhat run scripts/deploy.js --network localhost
```

4. Start the app

```
npm run dev
```
