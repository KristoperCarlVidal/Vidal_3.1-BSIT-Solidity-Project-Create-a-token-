# Project: Create a Token
The purpose of this project is to have a simple idea of how to create a token and how it also works, this code that I'm about to show you will answer the questions of how and why, and how this project will give you an understanding of how this runs.

## Description
Token.sol is a straightforward contract that demonstrates how to mint and burn tokens based on your total number of tokens. For example, if you have 1000 tokens, you can burn half of them and all that is left is 500, but if you burn another 1000 while you still have a token of 500, it will not change and will remain 500 since you cannot burn another 1000 tokens when all that is left is 500. Simply said, it enables you to produce, transfer, and track the tokens being processed on this project.

## Getting Started
Now, what are the requirements for this to work? The first is an Ethereum environment. Numerous Ethereum environments are available, one of which is called Remix - Ethereum IDE and can be used on our desktop or web browsers. Let me walk you through the steps:

## Installing
- We'll need to set up an environment where you can use Ethereum and whatever else you want as long as it supports Ethereum, such as some IDEs like Metamask, Remix, Geth, and so on.
- Once you settled on the IDE of your choice you will need to open the Token.sol and run it on the IDE that you have chosen.


## Executing program
- In Remix - Ethereum IDE you can click the Solidity Compiler Icon first on the left side screen if you don't have the auto compiler set yet
- After that, we proceed to the icon below Solidity Compiler which is Deploy and run transaction for you to interact with the mint and burn function as much as you want
- There are two functions which is (mint) you will be adding tokens into your specified address while (burn) will be deducting tokens into your specified address depending on the amount.

## Authors
- Vidal, Kristoper Carl V.
- Phone No. (09283674690)
- Facebook: Kristoper Carl (Creator.lun)

## License
This project is licensed under the MIT License - see the LICENSE.md file for details


