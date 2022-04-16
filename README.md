# Horoscope-NFT
This is a very cool and exciting project from "metaschool.so". You can create a react app that takes a users' date of birth, connects their metamask account and then mints an NFT to their address.

## Setting up the environment
Setup project directory and install Hardhat:
```ts 
mkdir HoroscopeNFT
cd HoroscopeNFT
npm init --yes
npm install --save-dev hardhat
npx hardhat
```

After running 'npx hardhat', choose "create a basic sample project".

## Install dependencies
```ts
npm install --save-dev @nomiclabs/hardhat-ethers ethers @nomiclabs/hardhat-waffle ethereum-waffle chai
npm install @openzeppelin/contracts
```

Open `contracts` folder inside HoroscopeNFT, you will see a `Greeter.sol` file present.
Add `HoroscopeNFT.sol` and `Base64.sol` files from this repository to `contracts` folder.

Now your Smart Contract is ready! Next you need to deploy it on-chain and make your front-end interact with it. For this refer to **metaschool.so**'s guided project from where this has been taken.
