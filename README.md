https://66bafbcd665218c245b2eefa--dashing-mochi-262f7b.netlify.app/

**Ethereum Payments DApp**
This project is a decentralized application (DApp) for handling Ethereum payments, including ERC-20 token transfers. It uses ethers.js for interacting with the Ethereum blockchain and React for the frontend. The DApp supports multiple chains like Polygon (Mumbai) and Sepolia.

**Features**
Ethereum Payments: Transfer ETH or ERC-20 tokens between accounts.
Token Selection: Choose and switch between different ERC-20 tokens.
Chain Support: Automatically detects network changes and updates token balances.
Recent Transactions: View and save recent transaction details.
Custom Contract Interaction: Interact with a custom PayPal-like smart contract for handling ETH payments.

**Tech Stack**
Frontend: React.js, Tailwind CSS
Blockchain Interaction: ethers.js
Contract Deployment: Sepolia, Polygon (Mumbai)
State Management: React Context API

**Usage**
Prerequisites
MetaMask: Install MetaMask to interact with the DApp.
Test Ether: Obtain test Ether from the Sepolia or Mumbai testnet faucet.

**Steps**
Connect MetaMask: Open the application and connect your MetaMask wallet.
Select Chain: Switch between Sepolia or Mumbai testnets using MetaMask.
View Balance: The application will automatically fetch and display your balance.
Select Token: Enter the ERC-20 token contract address to view the token balance and transfer tokens.
Transfer Funds: Enter the recipient address and amount, then click on "Transfer" to initiate the transaction.
Save Transaction: After a successful transfer, save the transaction details for future reference
