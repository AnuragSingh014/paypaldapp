https://66bafbcd665218c245b2eefa--dashing-mochi-262f7b.netlify.app/

**Ethereum Payments DApp**<br/>
This project is a decentralized application (DApp) for handling Ethereum payments, including ERC-20 token transfers. It uses ethers.js for interacting with the Ethereum blockchain and React for the frontend. The DApp supports multiple chains like Polygon (Mumbai) and Sepolia.

**Features**<br/>
Ethereum Payments: Transfer ETH or ERC-20 tokens between accounts.<br/>
Token Selection: Choose and switch between different ERC-20 tokens.<br/>
Chain Support: Automatically detects network changes and updates token balances.<br/>
Recent Transactions: View and save recent transaction details.<br/>
Custom Contract Interaction: Interact with a custom PayPal-like smart contract for handling ETH payments.<br/>

**Tech Stack**<br/>
Frontend: React.js, Tailwind CSS<br/>
Blockchain Interaction: ethers.js<br/>
Contract Deployment: Sepolia, Polygon (Mumbai)<br/>
State Management: React Context API<br/>

**Usage**<br/>
Prerequisites<br/>
MetaMask: Install MetaMask to interact with the DApp.<br/>
Test Ether: Obtain test Ether from the Sepolia or Mumbai testnet faucet.<br/>

**Steps**<br/>
Connect MetaMask: Open the application and connect your MetaMask wallet.<br/>
Select Chain: Switch between Sepolia or Mumbai testnets using MetaMask.<br/>
View Balance: The application will automatically fetch and display your balance.<br/>
Select Token: Enter the ERC-20 token contract address to view the token balance and transfer tokens.<br/>
Transfer Funds: Enter the recipient address and amount, then click on "Transfer" to initiate the transaction.<br/>
Save Transaction: After a successful transfer, save the transaction details for future reference<br/>
