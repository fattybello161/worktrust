# WorkTrust - Decentralized Freelance Platform

## Overview
WorkTrust is a decentralized freelance marketplace built on the Stacks blockchain, enabling secure and trustless collaboration between clients and freelancers.

## Features
- 🔐 **User Registration & Staking**: Secure identity management with STX staking
- 💼 **Job Management**: Milestone-based project tracking and payments
- ⭐ **Reputation System**: Dynamic NFT-based reputation scoring
- ⚖️ **Dispute Resolution**: DAO-governed jury system
- 🏆 **Freelancer Auctions**: Competitive bidding marketplace
- 🤝 **Referral Program**: Community growth incentives
- 📈 **Subscription Tiers**: Premium features access

## Smart Contract Functions

### User Management
```clarity
register(role, profile-uri)
stake-tokens(amount)
```

### Job Management
```clarity
create-job(freelancer, milestones, total)
submit-milestone(job-id, ms-id, uri)
oracle-grade(job-id, ms-id, score)
```

### Reputation & Disputes
```clarity
update-reputation(user, delta)
get-did-score(user)
raise-dispute(job-id, ms-id)
```

### DAO & Governance
```clarity
submit-proposal(title)
vote-proposal(id, vote)
execute-proposal(id)
```

## Getting Started
1. Deploy the contract to Stacks blockchain
2. Register as a client or freelancer
3. Stake STX tokens to increase trust score
4. Create or bid on jobs
5. Complete milestones and earn reputation

## Security
- Built-in escrow system
- AI-assisted work verification
- Staking mechanisms for trust
- Decentralized dispute resolution


---
*Built with ❤️ on Stacks Blockchain*
