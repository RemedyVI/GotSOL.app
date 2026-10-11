# GotSOL.app

**Agent-first USDC payments on Solana.**  
Non-custodial. Instant settlement. Built for AI agents.

GotSOL.app is a brand focused on making USDC payments simple and native for AI agents. Agents (or their operators) sign up, receive auto-generated non-custodial wallets, and can immediately accept USDC via payment links or Solana Pay QR codes. Vendors and merchants are welcome but secondary.

## Key Features
- Email or social signup → auto-generated Merchant + Owner wallets
- 0% fee on all incoming payments
- Instant USDC settlement to the Merchant Wallet
- Payment links and Solana Pay QR codes
- Gas abstraction (platform covers SOL network fees, with anti-abuse controls)
- Non-custodial (users control their keys)
- Compatible with x402 for agent micropayments

## Agent Payments & x402
GotSOL.app is designed for AI agents. We support standard Solana Pay payment links and QR codes and are compatible with the x402 protocol for agent micropayments. x402 lets agents discover, pay for, and access resources over HTTP using USDC on Solana with no accounts or API keys required. Wallet-based flows also support future identity and SSO-style agent authentication.

## Fees
| Action | Fee |
|--------|-----|
| Incoming payments (links, QR, cart) | **0%** |
| Merchant Wallet → Owner Wallet transfer | **0.25%** if account created on or before October 9, 2027<br>**0.5%** if account created on or after October 10, 2027 |

Early accounts (created on or before October 9, 2027) keep their 0.25% rate permanently. New accounts after the cutoff pay 0.5%. Fees apply only to the internal transfer from Merchant Wallet to Owner Wallet.

## Site Pages
- Feedback → agents@gotsol.app
- Privacy Policy
- Terms of Service

## Getting Started for Agents
1. Sign up at gotsol.app
2. Verify email and receive your non-custodial wallets
3. Generate a payment link or QR
4. Share it and get paid in USDC instantly

## Operations
- Domain: gotsol.app
- Repo: https://github.com/RemedyVI/GotSOL.app
- Ops email: agents@gotsol.app
- Operated with full compliance with applicable U.S. laws and regulations, including FinCEN and BSA requirements. Suspicious or fraudulent activity is flagged and reported to the appropriate authorities.

Not affiliated with the Solana Foundation, Solana Labs, or Solana Pay.
