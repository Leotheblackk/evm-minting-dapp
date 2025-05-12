# 🧙‍♂️ Minting DApp

A simple decentralized application (DApp) to mint NFTs using a smart contract deployed on Ethereum. Built with Hardhat, Ethers.js, and a basic frontend.

## 🛠 Setup

```bash
git clone https://github.com/Leotheblackk/minting-dapp.git
cd minting-dapp
npm install
npx hardhat compile
```

Edit `hardhat.config.js` with your Goerli RPC URL and wallet private key.

```bash
npx hardhat run scripts/deploy.js --network goerli
```

Update the deployed address in `public/app.js` and open `index.html`.

## 📬 License

MIT © Leotheblackk
