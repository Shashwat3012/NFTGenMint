# NFT GenMint

## An AI Powered NFT Generating and Minting Website

## Introduction

This is a simple web application that connects to your metamask wallet and generates a nft based on the prompt given using stable diffusion ai.

## YouTube Video of Working

[<img src="https://img.youtube.com/vi/fzmCRm3ghd0/hqdefault.jpg" width="600" height="300"
/>](https://youtu.be/fzmCRm3ghd0)

## Technology Stack & Tools

- Solidity (Writing Smart Contracts & Tests)
- Javascript (React & Testing)
- [Hardhat](https://hardhat.org/) (Development Framework)
- [Ethers.js](https://docs.ethers.io/v5/) (Blockchain Interaction)
- [React.js](https://reactjs.org/) (Frontend Framework)
- [NFT.Storage](https://nft.storage/) (Connection to IPFS)
- [Hugging Face](https://huggingface.co/) (AI Models)

## Prerequisites
- Install [NodeJS](https://nodejs.org/en/)

## Installation
### 1. Clone/Download the Repository

### 2. Install Dependencies:
`$ npm install`

### 3. Setup .env file:
Before running any scripts, you'll want to create a .env file with the following values (see .env.example):

- **REACT_APP_HUGGING_FACE_API_KEY=""**
- **REACT_APP_NFT_STORAGE_API_KEY=""**

You'll need to create an account on [Hugging Face](https://huggingface.co/), visit your profile settings, and create a read access token. 

You'll also need to create an account on [NFT.Storage](https://nft.storage/), and create a new API key.

### 4. Run tests
`$ npx hardhat test`

### 5. Start Hardhat node
`$ npx hardhat node`

### 6. Run deployment script
In a separate terminal execute:
`$ npx hardhat run ./scripts/deploy.js --network localhost`

### 7. Start frontend
`$ npm run start`

## Found a bug? resolve it

If you encounter a bug or have an improvement in mind, please follow these steps:

- Check the [GitHub Issues](https://github.com/Shashwat3012/NFTGenMint/issues) to see if the issue has already been reported.
- If not, open a new issue, describing the problem or your suggested enhancement.
- If you'd like to contribute, fork the repository, make the necessary changes, and submit a pull request.
