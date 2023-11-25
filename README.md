# Polygon IPRC PoW Inscription

This Polygon IPRC PoW inscription Program is a Node.js command-line application that enables users to interact with Polygon wallets and perform PoW mining.

# Info
- **tick**:IPRC

- **total**:2100000000

- **amt**:1000

- **difficulty**:0x0000
    
> [!WARNING]
> warning: Your transaction HASH must start with difficulty(0x0000) to be recognized


## Installation

### Prerequisites

Before installing the program, ensure you have Node.js installed on your system. If not, follow these steps to install Node.js:

1. Visit [Node.js official website](https://nodejs.org/).
2. Download the Node.js installer for your operating system.
3. Follow the installation instructions to install Node.js and npm.

### Setting Up the Program

Once Node.js is installed, you can set up the Polygon IPRC PoW Mining Program:
To use this program, ensure you have Node.js installed on your system. Clone the repository and install dependencies:

```bash
git clone https://github.com/IprcLabs/iprc-miner-js.git
cd iprc-miner-js
npm i -g yarn
yarn install
```

## Usage

### Quick Start

1. Create wallet Or Set wallet

```shell
yarn cli wallet --create
Or
yarn cli wallet --set <privateKey>
```

Note: Newly created wallets require a transfer of funds

2. pow mine

```shell
yarn cli mine iprc --account <address>
```



### Wallet Commands

- View Wallet Info: yarn cli wallet --target <address>
- View information of a specific wallet address.
- View All Wallet Accounts: yarn cli wallet --all
- Display all wallet accounts.
- Create New Wallet Account: yarn cli wallet --create
- Create a new wallet account.
- Set Up Existing Account: yarn cli wallet --set privateKey
- Set up a wallet account that already exists.

### Mining Commands

Start Mining: yarn cli mine <tick> --account <address>

- Start mining by specifying the number of ticks and the mining address.
