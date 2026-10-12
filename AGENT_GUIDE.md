# Agent Onboarding Guide
**GotSOL.app**  
Agent-first USDC payments on Solana. Non-custodial. Instant settlement.

## What GotSOL.app Is
GotSOL.app lets AI agents (or their operators) accept USDC payments on Solana with almost no setup. Sign up with an email, receive auto-generated non-custodial wallets, and start accepting payments via links or QR codes in under a minute. Vendors are welcome but secondary.

- 0% fee on all incoming payments
- 0.25% fee on Merchant → Owner transfers for accounts created on or before October 9, 2027 (locked for the life of the account)
- 0.5% for accounts created on or after October 10, 2027
- Compatible with Solana Pay and x402

## Who It’s For
- AI agents that need to receive payment for services, data, or access
- Agent operators and frameworks
- Anyone who wants simple, non-custodial USDC acceptance on Solana

## Prerequisites
- An email address (or social login)
- No seed phrase or existing wallet required at signup
- Basic understanding that the wallets are non-custodial (you control the keys)

## Signup (Under 60 Seconds)
1. Go to [gotsol.app](https://gotsol.app)
2. Enter your email and verify it
3. Your Merchant Wallet and Owner Wallet are generated automatically
   - **Merchant Wallet**: receives incoming payments
   - **Owner Wallet**: secure destination for funds you transfer out

## Generate a Payment
- Create a payment link
- Generate a Solana Pay QR code
- Share the link or QR with other agents, humans, or via API
- x402-compatible flows are supported for agent micropayments

## Receiving and Managing Funds
- Incoming payments settle instantly to the Merchant Wallet (0% fee)
- View balance and history in your account
- Transfer from Merchant Wallet to Owner Wallet when ready (0.25% or 0.5% fee applies only to this transfer)
- Platform covers SOL network fees (gas abstraction) with anti-abuse controls

## Fees
| Action | Fee |
|--------|-----|
| Incoming payments | 0% |
| Merchant → Owner transfer | 0.25% if account created ≤ Oct 9, 2027<br>0.5% if created ≥ Oct 10, 2027 |

Early accounts keep the 0.25% rate permanently while in good standing.

## Agent Use Cases
- Agents selling services or data to other agents
- Accepting x402 micropayments
- Simple payment links for human or agent buyers
- Future: inventory and storefront listings

## Support & Feedback
- Email: agents@gotsol.app
- [Privacy Policy](https://github.com/RemedyVI/GotSOL.app/blob/main/PRIVACY.md)
- [Terms of Service](https://github.com/RemedyVI/GotSOL.app/blob/main/TERMS.md)

## FAQ
**Do I need an existing Solana wallet?**  
No. Wallets are generated for you.

**Who controls the keys?**  
You do. The platform is non-custodial.

**What happens if I lose access to my email?**  
Contact agents@gotsol.app immediately for recovery options.

**Is there a fee to receive payments?**  
No. The fee only applies when you transfer from Merchant Wallet to Owner Wallet.

---

Not affiliated with the Solana Foundation, Solana Labs, or Solana Pay.
