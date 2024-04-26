# PupperCoin
# PupperCoin Crowdsale and ERC20 Token

Welcome to the PupperCoin crowdsale and ERC20 token repository! This project aims to fund the development of a decentralized network for tracking dog breeding activity globally and enabling humans to trace the genetic lineage of their pets. The PupperCoin token will serve as the native cryptocurrency of this network.

## Overview

PupperCoin will be launched through a crowdsale open to the public. The crowdsale will run for 24 weeks, during which users can send Ether (ETH) and receive PUP tokens in return. To ensure regulatory compliance and investor protection, the crowdsale contract will include provisions for refunds in case the fundraising goal is met and will cap the maximum amount raised at 300 Ether.

## Features

- **ERC20 Token**: PUP is an ERC20-compliant token, ensuring compatibility with existing Ethereum wallets and exchanges.
- **Crowdsale Contract**: The crowdsale contract will handle the entire token distribution process, minting tokens automatically and distributing them to buyers in one transaction.
- **Crowdsale Duration**: The crowdsale will run for 24 weeks.
- **Refunds**: Refunds will be enabled if the fundraising goal is met.

## Contract Details

The crowdsale contract will inherit the following features:
- **Crowdsale**: Manages the sale of tokens.
- **CappedCrowdsale**: Caps the maximum amount of Ether that can be raised.
- **TimedCrowdsale**: Specifies the duration of the crowdsale.
- **RefundableCrowdsale**: Enables refunds if the fundraising goal is met.
- **MintedCrowdsale**: Mints tokens and distributes them to buyers.

## Testing

The crowdsale and ERC20 token will be deployed and tested on the Kovan or Ropsten testnet to simulate real-world conditions and ensure functionality and security.

## Usage

1. Clone this repository to your local machine.
2. Install the necessary dependencies.
3. Deploy the crowdsale contract on the Kovan or Ropsten testnet.
4. Conduct the crowdsale by allowing users to send ETH and receive PUP tokens.

## Contributions

Contributions to enhance the functionality or security of the crowdsale and ERC20 token contracts are welcome. Simply fork the repository, implement your changes, and submit a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

Thank you for supporting the PupperCoin project! 🐾🚀
