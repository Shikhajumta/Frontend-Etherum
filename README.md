# Frontend Function
# Overview
This project demonstrates the integration of a blockchain-based application with MetaMask and a custom network. The following steps will guide you through setting up the project on your local machine.

# Prerequisites
Make sure you have the following installed:
Node.js and npm
Git
MetaMask

# Description
The Assessment Solidity contract manages an account balance with deposit and withdrawal capabilities exclusively for the contract owner. It initializes with an owner and a starting balance, providing functions to check the balance (getBalance), deposit funds (deposit), and withdraw funds (withdraw). The deposit function updates the balance and emits a Deposit event, while the withdraw function ensures sufficient funds before updating the balance and emitting a Withdraw event, utilizing a custom error (InsufficientBalance) for insufficient funds. The contract maintains security by restricting these operations to the owner and ensuring accurate balance updates through assertions.

# Getting Started
Clone the Repository
First, clone the repository from GitHub:

git clone <[repository-url](https://github.com/Shikhajumta/Frontend-Etherum.git)>
cd <repository-directory>

Install Dependencies
Inside the project directory, install the necessary dependencies:
/// npm install

Start the Local Blockchain Node
Open a second terminal in your VS Code and start a local Hardhat node:
/// npx hardhat node

Deploy the Smart Contract
Open a third terminal and deploy the smart contract to the local network:
/// npx hardhat run --network localhost scripts/deploy.js

Launch the Front-End
Back in the first terminal, launch the front-end application:
///npm run dev

Access the Application
The project will be running on your localhost, typically at:
http://localhost:3000/

MetaMask Configuration

Install the MetaMask extension in your browser if you haven't already.
Create a new MetaMask account or use an existing one.
Connect MetaMask to your custom network:
Open MetaMask and click on the network dropdown at the top.
Select "Custom RPC" or "Add Network".
Enter the details for your custom network (e.g., Localhost 8545).

Authors
Shikha Jumta jumtashikha000@gmail.com

License
This project is licensed under the MIT License - see the LICENSE file for details


