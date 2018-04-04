Uses some code from the SafeMath Library and the OpenZeppelin/zeppelin-solidity repo

This purpose of this solidity contract is to provide a tiered system for Ethereum Crowdsales.
In the case of this code, the Token is already created/minted, though this code can be modded to generate the tokens with each new ETH transfer.


The code transfers the ETH to a private wallet of your choosing (multi-sig) or otherwise which helps with security and preventing attacks.
This Contract also allows users to put a start and stop time on the crowdsale event, and lock up the remaining tokens to be returned to the contract owner.

