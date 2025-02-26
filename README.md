# Locked Savings Platform

![Image](https://github.com/user-attachments/assets/3c2c4103-4b09-42d8-ba34-564477195e25)

## Overview
FVKRY PRVNTA is a blockchain-based solution designed to enhance financial discipline among cryptocurrency and virtual asset owners. It allows users to lock their ETH and ERC-20 tokens in secure vaults that can only be accessed after a predefined lock period or during emergencies. The platform promotes long-term savings while providing flexibility for deposits and adjustable lock durations.

## Features
- Asset Locking:  
  Lock ETH and ERC-20 tokens in a secure smart contract vault.  
- Flexible Lock Periods:  
  Users can set lock durations for days, weeks, months or years.   
- Add-on Deposits:  
  Add more assets to your vault without resetting the lock period.  
- Secure and Transparent:  
  Built on Ethereum, leveraging smart contracts for transparency and trust.
- Partial or Full Withdrawal
  When the a lock expires the user can withdraw partial or the whole amount that was locked.
- Unlock Schedule
  Enables users to set an unlock schedule for when they will be accessing a portion of their locked assets within a given time period.
- Extend Lock Period
  Users can extend the lock period of a lock after it expires.
- Lock with a Goal
  User can define a lock as goal-based, the lock will expire when the the value of the locked assets reaches the goal set

## User Flow
1. Connect Wallet:  
   Connect a crypto wallet to access the platform.  
2. Dashboard Access:  
   Manage vaults, view balances, and track lock periods.  
3. Vault Creation:  
   Specify lock duration, type and assets to lock.  
4. Deposit Management:  
   Add more funds to an existing vault.  
5. Extenf Lock Period:  
   Extend the lock period after it expires.  

## How It Works
1. Lock ETH:  
   Use the platform to deposit ETH securely into a vault with a lock period.  

2. Lock ERC-20 Tokens:  
   Select supported tokens, approve the contract, and lock them in your vault.  

3. Smart Contract Logic:  
   - Locks assets for the specified duration.  
   - Only allows adding assets until the lock period ends.  
   - Extend lock period if it expires.  

4. Releases Funds:  
   After the lock duration or wh, users can withdraw assets directly to their wallets.

## Technology Stack
- Blockchain: Ethereum  
- Smart Contracts: Solidity (ERC-20 and ETH support)  
- Frontend: ReactJS with Vite
- Backend: Node.js and ExpressJS 
- Tools and Libraries: Hardhat, OpenZeppelin, WalletConnect, Wagmi and viem. 

## More
For detailed documentation on the smart contract, frontend and backend, view each individual repo readme file.
