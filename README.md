# NFT OpenSea Wallet Analyzer

This repository contains a Jupyter notebook that analyzes an Ethereum wallet's NFT holdings on the OpenSea platform. It fetches the wallet's collection data using the OpenSea API and visualizes the number of owned NFTs and their floor prices per collection.

## Features

- Retrieve NFT collection data from OpenSea using the provided API key and wallet address
- Generate a bar chart showing the number of owned NFTs per collection, color-coded by floor price ranges
- Calculate the total value of NFTs in the wallet based on floor prices

## Installation

1. Clone the repository:

```
git clone https://github.com/rimabuilds/nft-opensea-wallet-analyzer.git
```

2. Change into the project directory:

```
cd nft-opensea-wallet-analyzer
```

3. Install dependencies:

```
pip install -r requirements.txt
```

4. Create a `.env` file in the project directory with your OpenSea API key and wallet address:

```
OPENSEA_API_KEY=your_api_key
WALLET_ADDRESS=your_wallet_address
```

5. Launch Jupyter Notebook:

```
jupyter notebook
```

6. Open the `NFT_OpenSea_Wallet_Analyzer.ipynb` notebook and run the cells to generate the visualization.
