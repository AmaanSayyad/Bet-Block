# Bet-Block 🎰🏦

A decentralized gaming and lending platform built on blockchain technology, featuring NFT profiles, casino games, and DeFi lending services.

## 🏗️ Architecture

Bet-Block consists of three main components:

### 1. **betblock-contracts** - Smart Contracts
- **ProfileNFTContract.sol** - NFT-based user profiles
- **Roulette.sol** - Decentralized roulette game
- **Slots.sol** - Slot machine game implementation
- **AvalancheLending.sol** - Lending protocol for Avalanche network
- **PolygonLending.sol** - Lending protocol for Polygon network
- **BaseCase.sol** - Base contract for common functionality
- **CCIP Integration** - Cross-chain interoperability examples

### 2. **betblock-api** - Backend Services
- NFT management and metadata services
- Game state management
- Lending protocol integration
- Viem client integration for blockchain interactions

### 3. **betblock-react** - Frontend Application
- Modern React-based user interface
- Game interfaces (Roulette, Slots)
- Banking and lending dashboard
- NFT profile management
- Community features and leaderboards

## 🚀 Features

- **🎮 Casino Games**: Roulette and Slots with provably fair mechanics
- **🏦 DeFi Lending**: Cross-chain lending protocols
- **🖼️ NFT Profiles**: Unique user identity system
- **🌐 Multi-Chain**: Support for Avalanche and Polygon networks
- **🔗 Chainlink Integration**: Oracle and function services
- **👥 Community**: Leaderboards and social features

## 🛠️ Technology Stack

- **Smart Contracts**: Solidity, Hardhat
- **Frontend**: React, Material-UI
- **Backend**: Node.js, Express
- **Blockchain**: Ethereum, Avalanche, Polygon
- **Oracles**: Chainlink Functions and VRF
- **Development**: Hardhat, Viem

## 📁 Project Structure

```
Bet-Block/
├── betblock-contracts/     # Smart contracts and deployment scripts
├── betblock-api/          # Backend API services
├── betblock-react/        # Frontend React application
└── README.md              # This file
```

## 🚀 Getting Started

### Prerequisites
- Node.js 16+
- npm or yarn
- Hardhat
- MetaMask or similar wallet

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/AmaanSayyad/Bet-Block.git
   cd Bet-Block
   ```

2. **Install dependencies for each component**
   ```bash
   # Smart contracts
   cd betblock-contracts
   npm install
   
   # Backend API
   cd ../betblock-api
   npm install
   
   # Frontend
   cd ../betblock-react
   npm install
   ```

3. **Configure environment variables**
   - Copy `.env.example` files and configure your settings
   - Set up your private keys and RPC endpoints

4. **Deploy contracts**
   ```bash
   cd betblock-contracts
   npx hardhat deploy --network <your-network>
   ```

5. **Start the application**
   ```bash
   # Backend
   cd betblock-api
   npm start
   
   # Frontend
   cd betblock-react
   npm start
   ```

## 🎯 Smart Contract Deployment

The project includes deployment scripts for different networks:

- **Fuji Testnet** (Avalanche)
- **Mumbai Testnet** (Polygon)
- **Local Hardhat Network**

## 🔒 Security Features

- Provably fair gaming mechanics
- Secure lending protocols
- NFT-based identity verification
- Chainlink oracle integration for randomness

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Chainlink for oracle services
- OpenZeppelin for secure contract libraries
- Hardhat for development framework
- Viem for blockchain interactions

---

**Built with ❤️ by the Bet-Block Team**
