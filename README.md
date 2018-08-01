# Solidity Practice
Repository is created to  understand 
- State Variable
- Structures
- The import Statement
- Contracts


# Learn Solidity
Solidity Programing essentials and step by step learning


# Prerequisite
To Run these examples please follow following steps

## Installation
1. Install **Geth** (https://ethereum.github.io/go-ethereum/downloads/)
2. Install **Truffle** ```npm install -g truffle```
3. Start Test Network - There are three options
   - Use Test network using following comming
     - ```Geth --testnet``` **OR** 
     - ```Geth --rinkeby```
   - Create Private network 
   - Use ganache-cli
     - npm install -g ganache-cli
     - Run ganache-cli using following command
       - ```ganache-cli```
       - This will create Test network

# Compile, Deploy and Test Project
1. Inside that folder Compile with following command
   - ```truffle.cmd compile``` on Windows
   - ```truffle compile```

2. Deploy Contract with following command
   - ```truffle.cmd migrate```  on Windows
   - ```truffle migrate```


3. Test Contract with following command
   - ```truffle.cmd test```  on Windows
   - ```truffle test```
