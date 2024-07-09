# Metacraft-Atm

This project allow you to interect with your Metamask Wallet and use it as an Atm by doing some simple task in it Withdraw, Deposit and check balance.

## Description

This project is a simple ATM application that allows users to interact with their Metamask wallet. Built using React for the frontend and Solidity for the smart contract, it provides basic functionality for depositing and withdrawing Ether, as well as checking the balance. The application demonstrates how to integrate a web interface with the Ethereum blockchain, making it a practical example for students and developers interested in decentralized finance (DeFi) and blockchain technology.

The frontend is created using React, a popular JavaScript library for building user interfaces. It uses the useState and useEffect hooks to manage state and side effects, respectively. When the app loads, it checks if Metamask is installed and prompts the user to connect their wallet if it's not already connected. Once connected, the user can see their account details and balance. The app also provides buttons to deposit or withdraw 1 ETH, updating the balance accordingly.

The smart contract, written in Solidity, manages the balance and handles the deposit and withdrawal transactions. It includes basic security measures, such as ensuring that only the owner of the account can perform these actions. The contract also includes events to log deposits and withdrawals, which can be useful for tracking and debugging transactions.

Overall, this project is a great learning tool for understanding how to build decentralized applications (dApps) that interact with the Ethereum blockchain. It covers essential concepts such as smart contracts, blockchain interactions, and web3 integration, making it suitable for beginners and intermediate developers alike. By working on this project, you'll gain hands-on experience with blockchain development and get a glimpse into the exciting world of decentralized finance.

## Getting Started

### Requirments 
* You need to have Metamask Wallte.
* You need to have Vscode in you divice.
* Network connection.

### How to get 

* Opent the vscode terminal and write git clone https://github.com/Vansh001-0/Metacraft-Atm.git
  

### Executing program

* Open VS code in Metacraft-Atm.
* open terminal and write tese comand.

In first terminal write 
```
npm i 
```
In second terminal write 
```
npx hardhat node
```
In third terminal write 
```
npx hardhat run --network localhost scripts/deploy.js
```
Now come back to first terminal and write 
```
npm run dev
```

## License

This project is licensed under the MIT License.
