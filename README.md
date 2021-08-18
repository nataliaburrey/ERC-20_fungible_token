
# KaseiCoin ERC-20 fungible token  .

📌 Challenge 21

> " Crowdsale of KaseiCoin created with solidity. A fungible token that is ERC-20 compliant. Deployed with Remix IDE and tested with Ganache and MetaMask".
"


<img width="805" alt="Screen Shot 2021-08-17 at 4 55 58 PM" src="https://user-images.githubusercontent.com/80833988/129815451-59e547f3-f851-494c-80ed-b54655d30810.png">


## Table of content
- [Overview of the project](https://github.com/nataliaburrey/ERC-20_fungible_token#overview-of-the-project) 
- [Project steps](https://github.com/nataliaburrey/ERC-20_fungible_token#project-steps)
- [Software version control](https://github.com/nataliaburrey/ERC-20_fungible_token#software-version-control)
    - [Work with GitHub](https://github.com/nataliaburrey/ERC-20_fungible_token#work-with-github)
    - [How to install](https://github.com/nataliaburrey/ERC-20_fungible_token#how-to-install)
- [Helps recruiters](https://github.com/nataliaburrey/ERC-20_fungible_token#helps-recruiters)
- [License](https://github.com/nataliaburrey/ERC-20_fungible_token/blob/main/LICENSE)



## Overview of the project 

Creating a fungible token that is ERC-20 compliant and that will be minted by using a Crowdsale contract from the OpenZeppelin Solidity library.

The crowdsale contract is managing the entire crowdsale process, allowing users to send ether to the contract and in return receive KAI, or KaseiCoin tokens. Your contract will mint the tokens automatically and distribute them to buyers in one transaction.



## Project steps 

The steps for this Challenge are divided into the following sections:

    1. Create the KaseiCoin Token Contract
    
<img width="1111" alt="Screen Shot 2021-08-15 at 9 24 15 PM" src="https://user-images.githubusercontent.com/80833988/129511288-392dbbf9-7b42-4f7f-9f14-e11d7040dc9c.png">


    2. Create the KaseiCoin Crowdsale Contract
    
<img width="1109" alt="Screen Shot 2021-08-15 at 9 24 36 PM" src="https://user-images.githubusercontent.com/80833988/129511309-19d52cf7-162c-402e-aa1b-5944f0740043.png">

    3. Create the KaseiCoin Deployer Contract
    
<img width="946" alt="Screen Shot 2021-08-15 at 9 25 39 PM" src="https://user-images.githubusercontent.com/80833988/129511392-78b6a7f2-7c92-45b8-b457-7d33783d86fe.png">


    4. Deploy the Crowdsale to a Local Blockchain


##### Deploy the crowdsale to a local blockchain with Remix, MetaMask, and Ganache.

<img width="578" alt="Screen Shot 2021-08-17 at 5 13 33 PM" src="https://user-images.githubusercontent.com/80833988/129816723-bae44422-15b1-45ff-a3f4-8e70f51a9565.png">


<img width="375" alt="Screen Shot 2021-08-17 at 3 20 13 PM" src="https://user-images.githubusercontent.com/80833988/129816620-098c7d07-3ce5-4ea8-a1b7-d049c15215da.png">



https://user-images.githubusercontent.com/80833988/129816362-144cfbb1-163a-4999-a9de-173854a7c643.mov


<img width="352" alt="Screen Shot 2021-08-17 at 3 16 40 PM" src="https://user-images.githubusercontent.com/80833988/129816183-ccec70fb-a15b-4e74-87b8-f9ef9b842062.png">


##### Test the functionality of the crowdsale by using test accounts to buy new tokens and then checking the balances associated with those accounts.

<img width="1189" alt="Screen Shot 2021-08-17 at 3 28 15 PM" src="https://user-images.githubusercontent.com/80833988/129816397-21ff15c8-414f-4da8-a23d-2f92b028aaef.png">

<img width="304" alt="Screen Shot 2021-08-17 at 3 26 28 PM" src="https://user-images.githubusercontent.com/80833988/129816510-c5993edd-b43d-4d97-9daa-24dd0ea8e7e0.png">



##### After purchasing tokens with one or more test accounts, view the total supply of minted tokens and the amount of wei that has been raised in the crowdsale contract.

<img width="294" alt="Screen Shot 2021-08-17 at 3 27 53 PM" src="https://user-images.githubusercontent.com/80833988/129816458-27288993-0a6b-414e-9819-08a5bea471c3.png">


    5. Record a short video or take several screenshots that show the deployed contract in action.



https://user-images.githubusercontent.com/80833988/129816318-1d67a9b5-6ccf-4d4f-bd06-debb5706541f.mov

<img width="307" alt="Screen Shot 2021-08-17 at 3 21 26 PM" src="https://user-images.githubusercontent.com/80833988/129816265-10adbd01-c31b-4f71-b3d3-68d20236a155.png">

    6. Optional: Use OpenZeppelin to extend the functionality of your crowdsale contract 
    by adding time restrictions, refund capabilities, and a cap for the number of tokens that may be created.
    
 <img width="1169" alt="Screen Shot 2021-08-17 at 5 16 08 PM" src="https://user-images.githubusercontent.com/80833988/129816877-6a07cf59-f73e-40db-874d-68bea5410205.png">


## Software version control

[Remix IDE](https://remix.ethereum.org) used to interact with Etherium blockchain.

Remix - Ethereum IDE is an open source web and desktop application. It fosters a fast development cycle and has a rich set of plugins with intuitive GUIs. Remix is used for the entire journey of contract development as well as being a playground for learning and teaching Ethereum.

[MetaMask](https://metamask.io/) allows users to store and manage account keys, broadcast transactions, send and receive Ethereum-based cryptocurrencies and tokens, and securely connect to decentralized applications through a compatible web browser or the mobile app's built-in browser. 
For the purpose of challange we will create an enviroment and use paper trade Etherium to showcase crowdsale of our Token

[Ganache](https://www.trufflesuite.com/ganache) allows us to quickly fire up a personal Ethereum blockchain which you can use to run tests, execute commands, and inspect state while controlling how the chain operates. we will use it in this challenge to create a personal blockchain for rapid Ethereum distributed application development and test our crowdsale contract in a safe and deterministic environment.

### Work with GitHub
* Repository created on GitHub
* Files were  committed using command line
* Our repository is organized, and includes Resources folder with CSV  project files, 
* Jupyter Notebook with code runs without errors.
* Answers on nesassary questions are included

### How to install

* Save remote repo from GitHub to your computer (Desktop): in Terninal type:

```
cd desktop

git clone https://github.com/nataliaburrey/ERC-20_fungible_token.git
```

now you can find the folder ERC-20 fungible token on your desktop




## Helps recruiters

The project was created in collaboration with Berkeley Fintech Bootcamp team




📔 Contact me: 
📩 nataliaburrey@gmail.com

