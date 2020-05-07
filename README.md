# Blockchain-Star-Notary-Project
This project will be used to deploy smart contract on Rinkeby Test Network to manage and exchange information about stars.

# ERC-721 Token Name
## CheckmateToken

# ERC-721 Token Symbol
## CKMT

# Version of the Truffle 
## Truffle v5.1.24

# Version of 
## openzeppelin-solidity, "version": 2.1.2

# Rinkeby Test Net Address
## 0x3B3C254e206f45b7c8b2Fff2DCf390A007E0c5E1

# Task 1
- Add a name and a symbol for your starNotary tokens.
- Add a function lookUptokenIdToStarInfo, that looks up the stars using the Token ID, and then returns the name of the star.
- Add a function called exchangeStars, so 2 users can exchange their star tokens...Do not worry about the price, just write code to exchange stars between users.
- Write a function to Transfer a Star. The function should transfer a star from the address of the caller. The function should accept 2 arguments, the address to transfer the star to, and the token ID of the star.

# Task 2
- Add supporting unit tests, to test the following:
1. The token name and token symbol are added properly.
2. 2 users can exchange their stars.
3. Stars Tokens can be transferred from one address to another.

# Task 3
##Deploy your Contract to Rinkeby

- Edit the truffle.config file to add settings to deploy your contract to the Rinkeby Public Network.
- Helper Points:
1. Command used to deploy to Rinkeby truffle migrate --reset --network rinkeby
2. You will need to have your Metamask’s seed and Infura setup.
3. This was shown to you in detail in the lesson on Solidity, while creating ERC-20 tokens on Rinkeby.

# Task 4
- Modify the front end of the DAPP to achieve the following:
- Lookup a star by ID using tokenIdToStarInfo() (you will have to add code for this in your index.html and index.js files)


