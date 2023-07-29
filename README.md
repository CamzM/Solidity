# Solidity

# Project Title

This Solidity program is a simple "Create a Token" program written in the Solidity programming language. The purpose of this program is to create a contract that  stores details about the token, has a mapping of addresses to balances, has a mint function, and has a burn function.

## Description

This assessment is the final challenge of the course. For this assessment, we have to create a contract. As written in the instructions, the project has the following requirements:

1. Your contract will have public variables that store the details about your coin (Token Name, Token Abbrv., Total Supply)
2. Your contract will have a mapping of addresses to balances (address => uint)
3. You will have a mint function that takes two parameters: an address and a value. The function then increases the total supply by that number and increases the balance of the address by that amount.
4. Your contract will have a burn function, which works the opposite of the mint function, as it will destroy tokens. It will take an address and value just like the mint functions. It will then deduct the value from the total supply and from the balance of the address.
5. Lastly, your burn function should have conditionals to make sure the balance of account is greater than or equal to the amount that is supposed to be burned.

## Getting Started

### Executing program

* How to run the program
* Step-by-step bullets

To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.

Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., CreateaToken.sol). Copy and paste the following code from the file in the repository:

To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set to "0.8.18" (or another compatible version), and then click on the "Compile CreateaToken.sol" button.

Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the "CreateaToken" contract from the dropdown menu, and then click on the "Deploy" button.

Once the contract is deployed, you can interact with it by calling the sayHello function. Click on the "CreateaToken" contract in the left-hand sidebar, and then click on the mint function or burn. Finally, click on the "transact" button to execute the function.

## Authors

Contributors names and contact info

Metacrafter Camille :)
