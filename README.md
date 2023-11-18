# WICE

## Description:
 
WICE stands for Wide Investment Crypto Exchange. Its a DAO platform which provides the user very reliable and flexible use of crypto assets. Its built on keeping in mind to make crypto world very easy and understandable to each and every person. It provides token swapping, staking, unstaking, rewards claiming, converting fiat currencies to crypto and vice versa. WIE Token holders enjoy the advantage of getting discount on transactions as a benefit.

### Important Points :

- Uses non custodial wallet
- Provides swapping platform using sushiswap protocol
- Supports swapping of Polygon blockchain
- Provides staking, unstaking & reawrds claiming
- Provides fiat to crypto conversion ( using Wyre )
- Provides crypto to fiat conversion ( using Wyre )
- Sending & receiving tokens
- Provides transaction history of all supported tokens
- WIE Token holder enjoys discounts on transactions 

### Techologies Used:

- Hardhat
- Solidity

### List of Libraries/Framework used:

- Mocha
- Chai
- Ethers
- Web3
- Openzepplin
- BigNumber

### Directory layout
       
├── contracts                                      
├── scripts                   
├── test             
└── README.md

### How to install and run :

- Run `npm install` to install all dependencies

- Run `npx hardhat compile` to compile all the contracts

- Run `npx hardhat run scripts/deploy-script.js` to deploy all the contracts

### Run Test Cases :

- Run `npx hardhat test` to execute all the testcases of the contracts
- Run `npx hardhat test test/wie-token-test.js` to execute a WIE token testfile
- Run `npx hardhat test test/token-swap-test.js` to execute a Swap testfile