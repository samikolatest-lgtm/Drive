# Drive
🌐 Google Clarity Web3 Procurement Contract

This project provides a **Clarity smart contract** that simulates a **fair, transparent, and tamper-proof procurement system** for awarding contracts in a Web3 environment.  

The idea is to reimagine how enterprises (like Google) might use **decentralized bidding, evaluation, and awarding** of projects/contracts directly on the **Stacks blockchain** — ensuring transparency, auditability, and fairness.


✨ Core Features

- **Create Procurement Projects**  
  - Owners can publish new procurement opportunities (RFPs).  
  - Each project includes: title, description hash (IPFS/Arweave), budget, and deadline.

- **Vendor Participation**  
  - Vendors can submit bids tied to their blockchain wallet.  
  - Bids include cost + proposal hash (stored off-chain for efficiency).

- **Evaluator System**  
  - Project owners assign evaluators who can score proposals.  
  - Ensures decisions aren’t just cost-driven but also quality-driven.

- **Fair Winner Selection**  
  - After the deadline, a winner is selected based on **best value** = (score ÷ cost).  
  - Prevents undercutting while rewarding quality.

- **On-Chain Transparency**  
  - All critical actions (`project-created`, `bid-submitted`, `bid-scored`, `winner-selected`) are recorded on-chain as events.  



