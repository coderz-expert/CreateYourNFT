Create your NFT
## Getting Started

Before you begin, make sure to update the `env.local` files with the following configurations:
```bash
API_URL=     // Add the RPC URL here. You can create an account from alchemy.com and create a project. After that, you will receive the RPC URL.
PRIVATE_KEY=  // Add your private key here. You can get it from Metamask by clicking on your account, then on the menu (3-dot button), selecting Account details, and clicking on show Private Key.
PRIVATE_KEY=  // When you run `npx hardhat deploy scripts/deploy.js`, you will receive the public address of the contract.

```
Once you've updated the configurations, run the following commands:

```bash
npm install
npx hardhat compile
npx hardhat deploy scripts/deploy.js
```
After deploying the contracts, start the server by running the following command:
```bash
npx hardhat deploy scripts/mint-nft.js
```




