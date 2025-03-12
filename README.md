# 🎨 NFT Marketplace

<div align="center">

![Next.js](https://img.shields.io/badge/Next.js-13-black)
![Solidity](https://img.shields.io/badge/Solidity-0.8.20-blue)
![TypeScript](https://img.shields.io/badge/TypeScript-5-blue)
![License](https://img.shields.io/badge/License-MIT-green)

</div>

## 📝 Description

A modern, decentralized NFT (Non-Fungible Token) marketplace built with Next.js, Hardhat, and Ethereum smart contracts. This platform allows users to mint, buy, sell, and collect NFTs in a secure and user-friendly environment.

## ✨ Features

### Core Features
- 🎨 Create and mint NFTs with custom metadata
- 💰 List NFTs for sale with custom pricing
- 🛍️ Buy NFTs using ETH
- 🖼️ Browse NFT gallery
- 👛 Manage personal NFT collection
- 🔐 Secure wallet integration

### Technical Stack
- ⚡ Next.js 13 with App Router
- 🔗 Ethereum smart contracts (Solidity)
- 🎭 Hardhat development environment
- 🌈 RainbowKit for wallet connection
- 📦 IPFS for decentralized storage
- 🎨 TailwindCSS for styling
- 📱 Fully responsive design

## 🚀 Quick Start

### Prerequisites

- Node.js (v16.x or later)
- npm or yarn
- MetaMask or any Web3 wallet
- Git

### Installation

1. Clone the repository
```bash
git clone https://github.com/BallBean/nft_practice.git
cd nft_practice
```

2. Install dependencies
```bash
npm install
# or
yarn install
```

3. Set up environment variables
Create a `.env.local` file:
```env
NEXT_PUBLIC_PROJECT_ID=your_wallet_connect_project_id
NEXT_PUBLIC_ALCHEMY_API_KEY=your_alchemy_api_key
NEXT_PUBLIC_MARKETPLACE_ADDRESS=your_deployed_contract_address
```

4. Start local blockchain
```bash
npx hardhat node
```

5. Deploy contracts (in a new terminal)
```bash
npx hardhat run scripts/deploy.js --network localhost
```

6. Start the development server
```bash
npm run dev
# or
yarn dev
```

Visit [http://localhost:3000](http://localhost:3000)

## 📱 Usage

1. **Connect Wallet**
   - Click "Connect Wallet" button
   - Select your Web3 wallet
   - Approve the connection

2. **Create NFT**
   - Navigate to "Create" page
   - Upload image
   - Fill in NFT details
   - Set price
   - Click "Create NFT"

3. **Buy NFT**
   - Browse NFTs on homepage
   - Click on desired NFT
   - Click "Buy" button
   - Confirm transaction in wallet

4. **Manage Collection**
   - Go to "My NFTs" page
   - View owned NFTs
   - List/Unlist NFTs
   - Adjust prices

## 🔧 Smart Contract Features

- ERC721 token standard
- Marketplace functionality
- Secure ownership transfer
- Royalty support
- Access control
- Gas optimization

## 🧪 Testing

Run smart contract tests:
```bash
npx hardhat test
```

Run frontend tests:
```bash
npm run test
```

## 📦 Deployment

### Smart Contracts

1. Update network settings in `hardhat.config.js`
2. Deploy to testnet:
```bash
npx hardhat run scripts/deploy.js --network sepolia
```

### Frontend

1. Build the application:
```bash
npm run build
```

2. Start production server:
```bash
npm start
```

## 🔒 Security

- Reentrancy protection
- Access control
- Input validation
- Secure payment handling
- Error handling
- Rate limiting

## 🛣️ Roadmap

- [ ] NFT Collections
- [ ] Auction system
- [ ] Bulk minting
- [ ] Advanced filters
- [ ] Social features
- [ ] Multiple payment tokens
- [ ] Mobile app

## 🤝 Contributing

1. Fork the repository
2. Create feature branch
3. Commit changes
4. Push to branch
5. Open pull request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [OpenZeppelin](https://openzeppelin.com/)
- [Hardhat](https://hardhat.org/)
- [Next.js](https://nextjs.org/)
- [RainbowKit](https://www.rainbowkit.com/)
- [IPFS](https://ipfs.io/)
- [Ethereum](https://ethereum.org/)
