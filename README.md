# Eth-Avax-Module2-Project
# Solidity smart contract 
A Solidity smart contract named "Assessment" and a React frontend for interacting with the contract using the MetaMask wallet. The contract allows users to deposit and withdraw funds, check their balance, and perform some basic mathematical operations. The frontend provides a simple interface for users to interact with the contract functions.
# Description 
## 1. Solidity Smart Contract (Assessment.sol):

*    The contract has a state variable owner to store the address of the contract owner (deployer).
*    balance is a state variable that keeps track of the contract's balance.
*    The constructor initializes the contract owner and sets the initial balance during deployment.
*    The contract emits events Deposit and Withdraw when funds are deposited or withdrawn.
*    The contract provides functions for depositing, withdrawing, checking the balance, and performing mathematical operations (division, subtraction, and modulo).
*   The checkOwner function returns a fixed UID "21BCS11262".
*   Custom errors are defined, like InsufficientBalance, to handle specific conditions during contract execution.

## 2.  React Frontend (HomePage.jsx):
* The frontend uses React and MetaMask to interact with the deployed "Assessment" smart contract.
* The user interface displays the connected MetaMask account, the account balance, and the contract owner's UID.
* Users can deposit and withdraw 1 ETH from their account using the provided buttons.
* The frontend also features a basic calculator allowing users to input two numbers and perform division, subtraction, and modulo operations using the smart contract functions.
* The frontend communicates with the contract using the contract's address and ABI (Application Binary Interface)

# Execution (Steps to execute):
After cloning the github, you will want to do the following to get the code running on your computer.

1. Inside the project directory, in the terminal type: npm i
2. Open two additional terminals in your VS code
3. In the second terminal type: npx hardhat node
4. In the third terminal, type: npx hardhat run --network localhost scripts/deploy.js
5. Back in the first terminal, type npm run dev to launch the front-end.

After this, the project will be running on your localhost. 
Typically at http://localhost:3000/

# Authors 
Jaya Singh
# Video Walkthrough

