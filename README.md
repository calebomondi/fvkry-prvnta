# Locked Savings Platform

## Overview
FVKRY PRVNTA is a blockchain-based solution designed to enhance financial discipline among cryptocurrency and virtual asset owners. It allows users to lock their ETH and ERC-20 tokens in secure vaults that can only be accessed after a predefined lock period or during emergencies. The platform promotes long-term savings while providing flexibility for deposits and adjustable lock durations.

---

## Features
- Asset Locking:  
  Lock ETH and ERC-20 tokens in a secure smart contract vault.  
- Flexible Lock Periods:  
  Users can set lock durations and adjust them every three months.  
- Emergency Withdrawals:  
  Access locked assets in emergencies under defined conditions.  
- Add-on Deposits:  
  Add more assets to your vault without resetting the lock period.  
- Secure and Transparent:  
  Built on Ethereum, leveraging smart contracts for transparency and trust.

---

## User Flow
1. Register/Login:  
   Create an account or connect a crypto wallet to access the platform.  
2. Dashboard Access:  
   Manage vaults, view balances, and track lock periods.  
3. Vault Creation:  
   Specify lock duration and assets to deposit.  
4. Deposit Management:  
   Add more funds to an existing vault.  
5. Adjust Lock Period:  
   Extend the lock period after every three months if needed.  
6. Emergency Withdrawals:  
   Access funds under emergency conditions, subject to penalties or verification.  

---

## Technology Stack
- Blockchain: Ethereum  
- Smart Contracts: Solidity (ERC-20 and ETH support)  
- Frontend: ReactJ  
- Backend: Node.js with Supabase for authentication and database management  
- Tools: Hardhat, OpenZeppelin, and ethers.js  

---

## How It Works
1. Lock ETH:  
   Use the platform to deposit ETH securely into a vault with a lock period.  

2. Lock ERC-20 Tokens:  
   Select supported tokens, approve the contract, and lock them in your vault.  

3. Smart Contract Logic:  
   - Locks assets for the specified duration.  
   - Only allows adding assets until the lock period ends.  
   - Ensures emergency withdrawals follow pre-defined rules.  

4. Releases Funds:  
   After the lock duration, users can withdraw assets directly to their wallets.

---

## Getting Started
1. Clone the repository:
   ```bash
   git clone <repo_url>
   cd cloned-repo
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Deploy smart contracts:
   ```bash
   npx hardhat run scripts/deploy.js --network <network_name>
   ```

4. Start the development server:
   ```bash
   npm run dev
   ```

5. Connect your wallet and start saving securely!

---

## Future Enhancements 
- Support for multi-chain deployments (e.g., Polygon, Binance Smart Chain).  
- Gamification features to reward disciplined savers.  
- A mobile app for seamless access and management.  

---

## Contributing
Contributions are welcome! To get started:  
1. Fork the repository.  
2. Create a new branch for your feature/bug fix.  
3. Submit a pull request for review.  

---

## License
This project is licensed under the [MIT License](LICENSE).

---
