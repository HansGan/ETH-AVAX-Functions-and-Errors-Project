# FUNCTION AND ERRORS PROJECT

For this project, write a smart contract that implements the require(), assert() and revert() statements.

## Description

The project revolves around showcasing different types of error handling (require, revert, and assert) through a program on coin transactions. 
Essentially, it allows an owner account to buy and sell coins. Additionally it also allows the owner to apply for loan for extra wei.

The first function buy_coin() implements the require() error handling method where the user is unable to buy coins if his/her current balance is less than the total cost (computed as coin amount multiplied to coin cost). On the other hand, the second function called sell_coin() uses the same concept but implements the assert() method to prevent the unlikely scenario that the owner does not recieve the equivalent amount of wei after selling his/her coins to another account. Laslty, the borrow_loan() function utilizes the revert() method to essentially revert all changes to state variables if the owner does not own at least 3 coins. Overall, these function demonstrate the different usage of error handling methods in solidity.

## Getting Started

### Executing program

Simply run the code in REMIX IDE. To test the code make sure to compile then deploy the smart contract, use the default address for the owner address.
Make sure to add balances to the owner and the seller accounts you'll be using for you to be able to buy and sell coins. Moreover, carefully read each functions,
there are a total of 3 main functions that allows the main feautures usage, while the other two are for adding balances to the accounts and displaying them for easy
debugging if the transaction was successfull and to track the wei being transacted through the block.

In other words, here are the steps:
1. Open Remix IDE at https://remix.ethereum.org/
2. Create a solidity file with a file extention of .sol
3. Copy the solidity code from the ETH-AVAX-PROJECT here in this repository
4. Paste the copied code to the file you have created in the Remix IDE
5. Open the solidity compiler and compile your code
6. Open the deploy tab to deploy the smart contract
7. Perform your desired transactions using the defined functions

## Authors
Hans Matthew N. Gan (hansmatthewniervagan@gmail.com)
