# Web3.0 Smart Contract Lottery

This Solidity smart contract implements a Web3.0 lottery game, featuring ticket purchases, random number generation, and prize distribution. It leverages Chainlink’s Verifiable Random Function (VRF) for secure and tamper-proof randomness, along with Chainlink Automation for efficient and reliable contract management.

## Table of Contents

- [Web3.0 Smart Contract Lottery](#web30-smart-contract-lottery)
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

- You have installed [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
  - You'll know you did it right if you can run `git --version` and you see a response like `git version x.x.x`
- You have installed [Foundry](https://github.com/gakonst/foundry)
- You have a basic understanding of Solidity and smart contract development
- You have a MetaMask wallet or any other Ethereum wallet

## Installation

To install this project, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/jaym9000/SmartContract-Lottery.git
    ```

2. Navigate to the project directory:
    ```sh
    cd SmartContract-Lottery
    ```

3. Install the dependencies:
    ```sh
    forge install
    ```

## Usage

To use this project, follow these steps:

1. Compile the smart contracts:
    ```sh
    make build
    ```

2. Interact with the deployed contract using Foundry scripts or a frontend interface (frontend is a future project).

## Testing

To run tests for this project, use the following command:

```sh
make test
```

## Deployment

To deploy this project, follow these steps:

1. Deploy the smart contracts to the anvil testnet. You need to have it running in another terminal in order for it to deploy.
    ```sh
    make deploy
    ```

2. Deploy the smart contracts to the Sepolia testnet.
    ```sh
    make deploy ARGS="--network sepolia"
    ```
    This script sets up a Chainlink VRF subscription for you. If you already have an existing subscription, you can update it in the scripts/HelperConfig.s.sol file. Additionally, it will automatically register your contract as a consumer.

## License

This project is licensed under the MIT License. See the LICENSE file for more information.

# Thank you!

If you appreciated this, feel free to follow me or donate! *Below is JM's address*

ETH/Arbitrum/Optimism/Polygon/etc Address: 0x0f879bFF6c5cb229AFBaFCfFFE6C0FC29f95c796

[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://x.com/JM_Mahoro)
[![Linkedin](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jeanmarcc/)
