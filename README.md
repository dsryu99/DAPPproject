# Decentralized Star Notary Service

## Task 1
This Project is to Modify the StarNotary version 2 contract code to achieve the following:
- Add a name and a symbol for my starNotary tokens.
- Add a function lookUpTokenIdToStarInfo, that looks up the stars using the Token ID, and then returns the name of the star.
- Add a function called exchangeStars, so 2 users can exchange their star tokens...Do not worry about the price, just write code to exchange stars between users.
- Write a function to Transfer a Star. The function should transfer a star from the address of the caller. - The function should accept 2 arguments, the address to transfer the star to, and the token ID of the star.

## Task 2
- Add supporting unit tests, to test the following:
- The token name and token symbol are added properly.
- 2 users can exchange their stars.
- Stars Tokens can be transferred from one address to another.

## Task 3
- Deploy your Contract to Rinkeby
- Edit the truffle-config.js file to add settings to deploy your contract to the Rinkeby Public Network.
- Helper Points:
- Command used to deploy to Rinkeby: truffle migrate --reset --network rinkeby
- I need to have my Metamask’s seed and Infura setup.

## Task 4
- Modify the front end of the DAPP to achieve the following:
- Lookup a star by ID using tokenIdToStarInfo() (I added code for this in my index.html and index.js files)


## Information 
ERC-721 Token Name : Star Notary Token

ERC-721 Token Symbol : SNT

Token Address on the Rinkeby Network
https://rinkeby.etherscan.io/address/0xeb4c53c8fa5fec48febdbd3b25eebb8cb4ee1baf