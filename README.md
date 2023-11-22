
# Aptos IIT Bombay Winter School Stage 2 Challenge

## Video Explanation:

https://youtu.be/D4oQ4a5hUK8


### The Challenge

Build a simple full-stack (frontend + smart contract) game on Aptos. We recommend using the [Petra](https://chromewebstore.google.com/detail/petra-aptos-wallet/ejjladinnckdgjemekebdpeokbikhfci?pli=1) wallet and interacting with the testnet.

The UI of the game has these parts: 

1. A “Connect Wallet” button so users can link their wallets, using the [Wallet Adapter](https://aptos.dev/tutorials/build-e2e-dapp/add-wallet-support)
2. A big circle button that a user can click
3. A number, displayed prominently, which will show how many times the button has been clicked globally

### General Flow

1. A user connects their wallet first
2. The number on the page shows the total number of times any user has clicked the button. This is pulled from on-chain, in your contract. This number should update every few seconds.
3. The user can click on the big circle. This will [prompt the user](https://github.com/aptos-labs/aptos-wallet-adapter/tree/main/packages/wallet-adapter-react#examples) to sign and submit a transaction that increments the on-chain counter.

**Bonus features**

Create a leaderboard and show the top 10 users with the most clicks.

**Submission**

Please email your github repository along with a short demo video to demonstrate the working functionality of your project to satya@aptoslabs.com before Nov 22nd 11:59 PM IST. Please have the title of the email as “Aptos Winter School Coding Challenge Solution”. It would be a bonus if you can additionally send the vercel link of your deployed project.
