# Web3-Local-Basic-Storage
Makes a state change to a simple smart contract and then deploys it on a local blockchain (ganache CLI) or Rinkeby test net

Some file/folder descriptions: 
 >  - BasicStorage.sol is the basic storage example smart contract
 >  - deploy.py compiles the .sol code, connects to ganache, and then builds, signs, and sends a transaction

     
Usage: 
 > 1. ensure local enviorment is configured with Ganache (if not using rinkeby)
 > 2. change properties in deploy.py accordingly (update address key, chain id, private key)
 > 3. python deploy.py

  
Notes: 
> Either create an .env or run locally: export $PRIVATE_KEY={insert private key} to insert a private key (DON'T USE REAL). 
> Utilizes web3 and solcx. 
> Currently configred for local ganache enviorment 
