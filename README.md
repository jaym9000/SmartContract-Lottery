# Smart Contract Lottery with Foundry

This repository contains a comprehensive guide to building a smart contract lottery using the Foundry development environment. The project demonstrates the creation of a lottery contract with verifiable randomness using Chainlink VRF.

## Table of Contents

- [Smart Contract Lottery with Foundry](#smart-contract-lottery-with-foundry)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Testing](#testing)
  - [Deployment](#deployment)
  - [License](#license)

## Introduction

This project explores the Foundry smart contract development environment and provides a real-world example of creating a lottery contract. The lottery uses Chainlink VRF to ensure verifiable randomness in selecting the winner.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- You have installed [Foundry](https://github.com/gakonst/foundry)
- You have a basic understanding of Solidity and smart contract development
- You have a MetaMask wallet or any other Ethereum wallet

## Installation

To install this project, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/your-repo-name.git
    ```

2. Navigate to the project directory:
    ```sh
    cd your-repo-name
    ```

3. Install the dependencies:
    ```sh
    forge install
    ```

## Usage

To use this project, follow these steps:

1. Compile the smart contracts:
    ```sh
    forge build
    ```

2. Deploy the smart contracts to a local or test network:
    ```sh
    forge create --rpc-url <YOUR_RPC_URL> --private-key <YOUR_PRIVATE_KEY> src/Lottery.sol:Lottery
    ```

3. Interact with the deployed contract using Foundry scripts or a frontend interface.

## Testing

To run tests for this project, use the following command:

```sh
forge test
```

## Deployment

To deploy this project, follow these steps:

1. Ensure you have configured your environment variables for deployment (e.g., RPC URL, private key).
2. Deploy the contract using Foundry:
```
forge create --rpc-url <YOUR_RPC_URL> --private-key <YOUR_PRIVATE_KEY> src/Lottery.sol:Lottery
```

## License

This project is licensed under the MIT License. See the LICENSE file for more information.