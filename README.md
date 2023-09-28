# Swisstronik Challenge #4


Here are your tasks:
Deploy an ERC20 token
Mint tokens
Transfer at least 1 of your ERC20 tokens to 0x16af037878a6cAce2Ea29d39A3757aC2F6F7aac1


# Introduction
### Token
```
Name   : ARAPZZ
Symbol : ARPZ
```
### Smart Contract
```
0xcCeceeeCa51587634904C06C00cf26b3dB87126E
```
### Function Mint 100 Tokens
```
function mint100tokens() public {
    _mint(msg.sender, 100*10**18);
}
```
### Explorer Deploy
```
https://explorer-evm.testnet.swisstronik.com/tx/0xb2578cdaa7faa1cdec14a4cca3f03925be930bebe54e8d3e4bb59242fb855b29
```
### Explorer Minting
```
https://explorer-evm.testnet.swisstronik.com/tx/0xb7b6e171857b51682eac37d4dc055de94397efc2e312fe146c626a96cf47a44f```
```
### Explorer Transfer
```
https://explorer-evm.testnet.swisstronik.com/tx/0x01d302b4938f79c3ea1c8e706deb9317c8527cc06e45792895bb7e6f300a9e8c```
```

### Log Deploy
 <p align="center">
 <img height="100" height="auto" src="https://raw.githubusercontent.com/arapzz/images/main/swiss/Screenshot%202023-09-28%20082051.png">
 </p>

### Log Transfer 
 <p align="center">
 <img height="300" height="auto" src="https://raw.githubusercontent.com/arapzz/images/main/swiss/Screenshot%202023-09-28%20082221.png">
 </p>

### Log Balance 0x16af037878a6cAce2Ea29d39A3757aC2F6F7aac1
 <p align="center">
 <img height="100" height="auto" src="https://raw.githubusercontent.com/arapzz/images/main/swiss/Screenshot%202023-09-28%20082304.png">
 </p>
     
# Usage
```
npm install --save-dev hardhat
npx hardhat
npm install --save-dev @nomicfoundation/hardhat-toolbox
npm install @openzeppelin/contracts
npm install @swisstronik/swisstronik.js
npx hardhat run scripts/deploy.js
npx hardhat run scripts/mint.js
npx hardhat run scripts/transfer.js
```
