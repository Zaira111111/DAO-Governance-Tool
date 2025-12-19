# 🏛️ DAO Governance Tool

A fully decentralized on-chain governance system that allows token holders to propose, vote, and execute changes.

## 🚀 How it Works
1. **Governance Token:** Users hold tokens that represent their voting power.
2. **Proposing:** Any user with enough tokens can create a proposal (e.g., "Change Treasury Fee").
3. **Voting:** Token holders vote (For, Against, or Abstain) during the voting period.
4. **Execution:** If the proposal passes, it is automatically executed on-chain.

## 🛠️ Tech Stack
- **Solidity** (Smart Contracts)
- **OpenZeppelin Governor** (Standard for DAO security)
- **Hardhat** (Development environment)
- **Ethers.js** (Interacting with the DAO)

## 📁 Key Features
- **Voting Delay:** Time between proposal and voting starts.
- **Voting Period:** Duration for which voting stays open.
- **Quorum:** Minimum % of total supply needed for a vote to be valid.

## 🔧 Setup & Installation
1. Install dependencies: `npm install @openzeppelin/contracts`
2. Compile: `npx hardhat compile`
3. Deploy: `npx hardhat run scripts/deploy.js`
