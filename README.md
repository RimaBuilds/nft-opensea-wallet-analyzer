# NFT OpenSea Wallet Analyzer

This repository contains a quick and simple Jupyter notebook that analyzes an Ethereum wallet's NFT holdings on the OpenSea platform. It fetches the wallet's collection data using the OpenSea API and visualizes the number of owned NFTs and their floor prices per collection like the graph below.
This script analyzes the collection of NFTs owned by a user and visualizes the data in a bar chart.
It fetches the data using the Opensea API and then filters, sorts, and plots the data.

## Functions:
- load_environment_variables: loads the API key and wallet address from a .env file
- fetch_owner_collections: fetches the collections owned by the given wallet address
- create_dataframe: creates a dataframe from the fetched collections
- filter_dataframe: filters the dataframe to remove rows with unavailable or very low floor prices
- calculate_total_value: calculates the total value of NFTs in the wallet
- get_color: helper function to determine the color of a bar based on its floor price
- plot_data: plots the data in a horizontal bar chart

![NFT Portfolio Graph](NFT%20port%20graph.png "NFT Portfolio Graph")

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
