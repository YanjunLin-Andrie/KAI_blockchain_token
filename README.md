![header](pics/header.png)
# KaseiCoin on Chain
**KAI (KaseiCoin)** is a new monetary system, the KAI crowdsale is launched through blockchain. KaseiCoin is a fungible token that is ERC-20 compliant. By using this service, customers can convert their money to KaseiCoin.
---
---

Content incudes:

* [Technologies](#technologies)

* [App Development](#app-development)

* [App Demo](#app-demo)

* [Contributors](#contributors)

---

## Technologies
>This project leverages python 3.7

* [Solidity](https://docs.soliditylang.org/en/v0.8.15/) - object-oriented, high-level language for implementing smart contracts

* [Remix IDE](https://remix.ethereum.org/) - allows developing, deploying and administering smart contracts for Ethereum like blockchains. It can also be used as a learning platform

* [OpenZeppelin](https://www.openzeppelin.com/) - provides seurity products to build, automate, and operate decentralized applications.

---

## App Development
* Created KaseiCoin.sol
    * Imported ERC20, ERC20Detailed, and ERC20Mintable from OpenZeppelin
    * Built KaseiCoin contract with constructor
    * Compiled the contract

![compile1](pics/compile1.png)

* Created KaseiCoinCrowdsale.sol
    * Inported KaseiCoin.sol, Crowdsale, MintedCrowdsale, CappedCrowdsale, TimedCrowdsale, and RefundablePostDeliveryCrowdsale
    * Built KaseiCoinCrowdsale contract with constructor
    * Compiled the contract 
    * Built KaseiCoinCrowdsaleDeployer contract with constructor
    * Compiled the contract

![compile2](pics/compile2.png)

![compike3](pics/compile3.png)

## * **Deploy the KaseiCoinCrowdsaleDeployer contract on MetaMask with specified name, symbol, and address**

![deploy1](pics/deploy1.png)

## * **Confirm deployment with MetaMask**

![mm1](pics/mm1.png)

## * **Deploy the KaseiCoinCrowdsale contract with provided address and it provides functions described in the contract**

![deploy3](pics/deploy3.png)

![deploy4](pics/deploy4.png)

## * **Deploy the KaseiCoin contract with provided address and it provides functions described in the contract**

![deploy5](pics/deploy5.png)

![deploy6](pics/deploy6.png)

---

## App Demo

### Test the App by purchasing tokens with 2 test accounts, then display the total supply of minted tokens and the amount of wei that has been raised in the crowdsale contract. 

## Step1: Specify the number of KAI trying to puchase

![buy1](pics/buy1.png)

## Step2: Put in the account address of the user trying to purchase KAI and press `buyTokens`

![buy2](pics/buy2.png)

## Step3: Confirm the purchase on MetaMask

![mm2](pics/mm2.png)

## Step4: Check the amount of tokens has been sold by clicking `weiRaised`

![buy3](pics/buy3.png)

## Step5: Check the amount of tokens has been minted by clicking `totalSupply`

![buy4](pics/buy4.png)

## Step6: Repeat Step1 - Step5 and confirm total tokens sold and minted

![buy5](pics/buy5.png)

![buy6](pics/buy6.png)

---

## Contributors

**Yanjun Lin Andrie** <span>&nbsp;&nbsp;</span> |
<span>&nbsp;&nbsp;</span> email: yanjun.lin.andrie@gmail.com <span>&nbsp;&nbsp;</span>|
<span>&nbsp;&nbsp;</span> [<img src="pics/linkedin.png" alt="in" width="20"/>](https://www.linkedin.com/in/yanjun-linked/)

**UC Berkeley Extension**

---

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)


---

## Evaluation Evidence


![compile1](pics/compile1.png)
![compile2](pics/compile2.png)
![compike3](pics/compile3.png)
![deploy1](pics/deploy1.png)
![mm1](pics/mm1.png)
![deploy3](pics/deploy3.png)
![deploy4](pics/deploy4.png)
![deploy5](pics/deploy5.png)
![deploy6](pics/deploy6.png)
![buy1](pics/buy1.png)
![buy2](pics/buy2.png)
![mm2](pics/mm2.png)
![buy3](pics/buy3.png)
![buy4](pics/buy4.png)
![buy5](pics/buy5.png)
![buy6](pics/buy6.png)