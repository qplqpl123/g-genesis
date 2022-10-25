# Create Your First NFT with Infura and StarkNet

## Prerequisites

- node (tested on v16.xx.x)
- npm (tested on v8.xx.x)
- Infura Web3 account with StarkNet enabled
- Infura IPFS account with dedicated gateway
- basic knowledge of ERC721 standard

## Setting up

Install all the dependencies of this project:

```bash
npm install
```

Create a new `.env` file:

```bash
cp .env.example .env
```

Edit this file with the Infura network and IPFS information (note that some of those are optional).

Then source it:

```bash
source .env
```

## Run

```bash
node index.js
```
