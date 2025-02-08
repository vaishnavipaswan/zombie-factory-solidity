# 🧟‍♂️ Zombie Factory Smart Contract  
**CryptoZombies - Beginner to Intermediate Solidity Contracts**  

## 📜 Overview  
This repository contains the **Zombie Factory** smart contract from the CryptoZombies Solidity course. It is designed as an introduction to Solidity for beginners and covers essential concepts like:  
- Structs and Arrays  
- Mapping and Storage  
- Function Modifiers  
- Events and State Variables  

## 🚀 Features  
- Create and manage **zombies** with unique attributes.  
- Generate **random zombie DNA** for each new zombie.  
- Store and retrieve zombie data using **mappings**.  
- Use Solidity **events** to interact with the blockchain.  

## 🏗️ Smart Contract  
The main contract is written in **Solidity** and can be found in [`ZombieFactory.sol`](./ZombieFactory.sol).  

## 🛠️ Setup & Compilation  
To use this contract, you need **Remix IDE** or a Solidity-compatible environment like Hardhat or Truffle.  

### **Remix IDE**  
1. Open [Remix IDE](https://remix.ethereum.org/).  
2. Create a new file and copy the contract code.  
3. Compile using **Solidity Compiler**.  
4. Deploy using **Injected Web3** (MetaMask).  

### **Using Hardhat (Optional)**  
1. Install dependencies:  
   ```sh
   npm install --save-dev hardhat
2. Compile:
   ```sh
   npx hardhat compile
3. Deploy (if you have a script set up):
    ```sh
    npx hardhat run scripts/deploy.js --network localhost

## 🙌 Credits
Based on the CryptoZombies Solidity course by Loom Network.
