# MiniProject
## ABOUT
A blockchain-based voting system that preserves voter privacy and increases accessibility, while keeping the voting system transparent, secure, and cost-effective. The system implements a voting framework that utilizes ethereum’s blockchain and smart contracts to achieve voter administration and auditable voting records. The implementation was deployed on ethereum’s test network to demonstrate usability, scalability, and efficiency.

##Author: Varshith_BR

Pre requisites:
1. Node JS
2. Ganache
3. Metamask extension in the browser, preferably chrome.

## SET UP INSTRUCTIONS

Open ganache and select quick start ethereum.

Open your browser and configure metamask. Create a wallet and store yourSecret Recovery Phrase in a safe place.

#### Configure MetaMask to Use Ganache
Open MetaMask extension.

Click the network selector (top center), then "Add network manually".

Fill in:

Network Name: Ganache Localhost

RPC URL: http://127.0.0.1:7545

Chain ID: 1337 or 5777 (Ganache UI shows the right one)

Currency Symbol: ETH

Save and switch to this network.

#### Importing an account from ganache to metamask
1. Open ganache and select show keys on any account. The show keys button is the key icon.
2. Copy the private key and click done.
3. Open the metamask menu which can be accessed by clicking the profile picture and select import account.
4. Paste the private key copied from ganache and click import.

#### Cloning the project


cd E-Voting_System_Blockchain

npm i

truffle compile

truffle migrateortruffle migrate --reset for subsequent runs

npm start

The project will open in the browser and metamask will ask you to select an account. Select the account we had imported earlier.
