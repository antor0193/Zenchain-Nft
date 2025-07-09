# Zenchian NFT - Cross Chain

A basic cross-chain capable NFT project using Ethereum and Polygon.

## Features

- ERC-721 NFT Minting
- Burn for cross-chain (mocked)
- Frontend for minting
- Hardhat deploy script

## How to Use

1. Install dependencies:
   ```
   npm install
   ```

2. Compile contracts:
   ```
   npx hardhat compile
   ```

3. Deploy to Goerli:
   ```
   npx hardhat run deploy/deploy.js --network goerli
   ```

4. Open `frontend/index.html` in a browser with MetaMask installed.
