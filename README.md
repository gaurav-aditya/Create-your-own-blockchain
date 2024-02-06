# Create your own (basic) blockchain

Welcome to the basic blockchain GitHub repository! In this, we'll be creating a very basic blockchain using Java. This blockchain will implement a simple proof of work (mining) system, allowing you to marvel at the possibilities of blockchain technology.

## Requirements

To follow along with this tutorial, you will need the following:

- Java and JDK installed.
- Eclipse or another IDE/Text Editor of your choice.
- Basic understanding of object-oriented programming (OOP) concepts.

## Making the Blockchain

A blockchain is essentially a chain or list of blocks. Each block contains its own digital fingerprint (hash), the hash of the previous block, and some data (which could be transactions, for example).

Here are some key points about our blockchain implementation:

- **Hash = Digital Fingerprint**: Each block contains a hash that serves as its digital fingerprint.
- **Chaining Blocks Together**: Each block's hash is calculated, in part, from the previous block's hash. This chaining ensures the integrity of the blockchain.
- **Proof of Work Mining**: Our blockchain requires proof of work mining to validate new blocks.
- **Validity Check**: The blockchain can be checked to ensure that its data is valid and unchanged.

## Getting Started

To start creating your blockchain:

1. Clone or download this repository to your local machine.
2. Import the GSON library (`gson-2.8.2.jar`) as a dependency.
3. Ensure you have JDK 1.8.0_77 or compatible version installed.

## Repository Structure

- **`src/`**: Contains the Java source code for the blockchain implementation.
- **`lib/`**: Contains the GSON library (`gson-2.8.2.jar`).
- **`README.md`**: You're currently reading it! This file provides an overview of the repository and instructions for getting started.
- **`LICENSE`**: The license under which this repository is distributed.
- **`contact`**: Contact information for the repository owner

## Blockchain

If you have any questions or need further assistance, feel free to contact the tutorial author at echoaditya@proton.me.

## About Me

I'm Aditya Gaurav, a passionate developer exploring the world of blockchain and distributed ledger technology. To learn more about my projects and interests, visit my [website](https://gaurav-aditya.github.io).

Happy coding and exploring the world of blockchain!

--- 

**Disclaimer**: This repository is intended for educational purposes only. It provides a basic understanding of blockchain concepts and should not be used for production-grade applications without proper validation and security measures.
