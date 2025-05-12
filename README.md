# BlockID - Blockchain Identity Management

A decentralized identity management system built on Ethereum blockchain using Next.js, React, and IPFS.

## Getting Started

### Prerequisites

- Node.js (v16 or later)
- npm or yarn
- Metamask wallet
- Alchemy API key for Sepolia testnet
- Pinata API key and secret for IPFS storage

### Setup

1. Clone the repository
   ```bash
   git clone https://github.com/yourusername/blockid.git
   cd blockid
   ```

2. Install dependencies
   ```bash
   npm install
   # or
   yarn install
   ```

3. Environment Variables
   
   Copy the `.env.example` file to create a new `.env.local` file:
   ```bash
   cp .env.example .env.local
   ```
   
   Fill in your own values in the `.env.local` file.

4. Run the development server
   ```bash
   npm run dev
   # or
   yarn dev
   ```

5. Open [http://localhost:3000](http://localhost:3000) in your browser

## Smart Contract Development

The smart contracts are built with Hardhat. To compile and deploy the contracts:

```bash
# Compile contracts
npx hardhat compile

# Deploy to Sepolia testnet
npx hardhat run scripts/deploy.js --network sepolia
```

## Learn More

To learn more about the technologies used in this project:

- [Next.js Documentation](https://nextjs.org/docs)
- [Hardhat Documentation](https://hardhat.org/getting-started/)
- [Ethers.js Documentation](https://docs.ethers.io/v5/)
- [IPFS Documentation](https://docs.ipfs.tech/)

## License

This project is licensed under the MIT License.
