# blockchain-Ethers.js-Assignemnt
Markdown
# 🔗 Blockchain Ethers.js Assignment

This repository contains a blockchain assignment focused on interacting with Ethereum smart contracts using **Ethers.js (v6)** and **Truffle**. It demonstrates how to securely connect to a blockchain network, manage environment variables, and execute contract functions.

## 🛠️ Tech Stack
* **Ethers.js (v6.16.0):** For connecting to the Ethereum network and interacting with smart contracts.
* **Truffle:** Development environment and testing framework for blockchains using the Ethereum Virtual Machine (EVM).
* **Dotenv:** For securely managing environment variables like private keys and RPC URLs.
* **Node.js:** JavaScript runtime environment.

## 🚀 Getting Started

### 1. Prerequisites
Make sure you have [Node.js](https://nodejs.org/) installed on your machine. You will also need a local blockchain network like [Ganache](https://trufflesuite.com/ganache/) running for local development.

### 2. Installation
Clone the repository and install the required dependencies:
```bash
git clone [https://github.com/your-username/blockchain-Ethers.js-Assignemnt.git](https://github.com/your-username/blockchain-Ethers.js-Assignemnt.git)
cd blockchain-Ethers.js-Assignemnt
npm install
3. Environment Variables Setup
Create a .env file in the root directory of the project. Do not commit this file to version control. Add your specific keys and RPC URLs:

مقتطف الرمز
PRIVATE_KEY="your_wallet_private_key_here"
RPC_URL="[http://127.0.0.1:7545](http://127.0.0.1:7545)" # Example for local Ganache network
4. Running the Project
Compile your smart contracts using Truffle:

Bash
truffle compile
Run your Ethers.js scripts (replace script.js with your actual script name):

Bash
node script.js
🔒 Security Note
Never share or commit your .env file or expose your private keys.

Always use test accounts with no real funds (like Ganache generated accounts) during development.

🤝 Author
Developed as part of a Computer Science Blockchain assignment.
