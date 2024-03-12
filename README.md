# DegenToken

A decentralized application (DApp) for managing and utilizing the Degen token, a custom ERC-20 token built on the Ethereum blockchain.

## Description

DegenToken is an ERC-20 token smart contract deployed on the Ethereum blockchain using the Hardhat framework. The token comes with additional functionalities such as minting, burning, and a redemption feature for specific items.

### Features

- **Minting**: The owner of the contract can mint new Degen tokens and distribute them to specific addresses.
- **Burning**: Token holders can burn their own tokens based on a specific item serial number, which grants them access to exclusive items in the redemption shop.
- **Redemption Shop**: The contract has a predefined redemption shop with three items available for redemption: 
    1. Pan
    2. Ceramic Bowl
    3. Ladder
   Users can redeem these items by burning a specific quantity of tokens.
- **Owner Advantage**: The contract provides a function for the owner to burn tokens from a target address, assuming the target address holds more than 5 tokens.

## Getting Started

### Installing

To interact with the DegenToken contract, follow these steps:

1. Clone the repository.
2. Install the required dependencies using the following command:
    ```bash
    npm install
    ```

### Executing program

To deploy and interact with the DegenToken contract, follow these steps:

1. Deploy the contract to the Ethereum blockchain using Hardhat:
    ```bash
    npx hardhat run scripts/deploy.js --network <your-network>
    ```
2. You can deploy the contract using its address in Remix to interact with its functions.

## Authors

Joselyn Riana Manoj 
Email: joselynriana@gmail.com

## License

This project is licensed under the MIT License.
