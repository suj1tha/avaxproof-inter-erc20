# Metacrafters ETH + AVAX PROOF: Intermediate EVM Course - ERC20

## Description

SujithaToken is an ERC20-compliant token deployed on the Ethereum blockchain. It includes standard ERC20 features such as token transfers and balance tracking, along with burnable capabilities, allowing users to destroy tokens, and an owner-controlled mint function to issue new tokens. The contract is built using OpenZeppelin's secure and industry-standard library, ensuring robust security and compatibility.

## Getting Started

### Installing

To deploy and interact with the SujithaToken, you'll need a development environment like Hardhat or Truffle. Ensure you have Node.js and npm installed.

1. Clone the repository: `git clone https://github.com/suj1tha/avaxproof-inter-erc20`
2. Install dependencies: `npm install`
3. Ensure OpenZeppelin Contracts are installed: `npm install @openzeppelin/contracts`

### Executing Program

To deploy the contract on a local or test network:

1. Compile the contract: `npx hardhat compile`
2. Deploy the contract (customize deployment script as needed): npx hardhat run scripts/deploy.js --network sepolia
3. Interact with the deployed contract via Hardhat console or a web3-enabled application.

### OR

Execute code in https://remix.ethereum.org/

## Authors

Sujitha

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.
