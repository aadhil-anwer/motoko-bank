Basic Bank Project

Welcome to the Basic Bank Project. This is a straightforward banking application written in Motoko and deployed on the Internet Computer Protocol (ICP) Blockchain. This project is designed to demonstrate essential banking functions such as account creation, balance inquiry, deposits, and withdrawals.


Table of Contents

Project Overview
Prerequisites
Installation
Usage
Testing
Contributing
License

Project Overview

The Basic Bank Project is engineered to provide a simple yet comprehensive example of a banking system. The application's functionality includes:


Account Creation: Enables users to create an account with a unique identifier.
Balance Inquiry: Allows users to check their current balance.
Deposits: Provides a feature for users to deposit money into their account.
Withdrawals: Allows users to withdraw money from their account.

This project is built using the Motoko programming language, which is specifically designed for creating decentralized applications (dApps) on the ICP Blockchain.


Prerequisites

Before you begin, ensure you have met the following requirements:


You have installed the latest version of the DFINITY Canister SDK.
You have a Windows/Linux/Mac machine with a recent version of Node.js installed.

Installation

To install the Basic Bank Project, follow these steps:


Clone the repository

git clone https://github.com/your-username/basic-bank-project.git

Navigate into the project directory

cd basic-bank-project

Install the dependencies

npm install

Build the project

dfx build

Usage

To use the Basic Bank Project, follow these steps:


Start the local network

dfx start --background

Deploy the canisters

dfx canister install --all

Open a web browser and navigate to the local network address to interact with the banking interface.

Testing

To run tests on the Basic Bank Project, execute the following command:


dfx test

Contributing

Contributions to the Basic Bank Project are welcomed. Before contributing, please read through our contributing guidelines.


License

The Basic Bank Project is licensed under the MIT license.


We appreciate your interest in our Basic Bank Project. We look forward to your contributions and feedback.
