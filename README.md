# sBTC Payment Gateway

> Stripe for sBTC - The easiest way to accept Bitcoin payments

**Live Demo:** https://sbtc.netlify.app  
**Competition:** Stacks Builders Challenge 2025

## What It Does

A payment gateway that makes accepting Bitcoin as simple as accepting credit cards. Built on Stacks with sBTC for 100% Bitcoin finality.

## Features

- Clean Stripe-like interface
- Real wallet integration (Xverse/Leather)
- sBTC testnet transaction processing
- Developer-friendly APIs
- Mobile responsive design

## Quick Start

```html
<!-- Include the SDK -->
<script src="https://sbtc.netlify.app/sdk.js"></script>

<script>
// Create payment button
const gateway = new SBTCPaymentGateway({
  apiKey: 'your-key'
});

const button = gateway.createPaymentButton({
  amount: 0.001,
  onSuccess: () => console.log('Payment complete!')
});
</script>
```

## Demo Instructions

1. Visit https://sbtc.netlify.app
2. Install Xverse or Leather wallet
3. Switch wallet to Stacks testnet
4. Get test tokens from https://explorer.hiro.so/sandbox/faucet
5. Connect wallet and test payment

## Tech Stack

- Frontend: HTML, CSS, JavaScript
- Blockchain: Stacks, sBTC
- Wallets: Xverse, Leather
- Deployment: Netlify

## Competition Entry

Built for Stacks Builders Competition - creating infrastructure to unlock Bitcoin's $1 trillion economy through simple payment processing.

## Repository Structure

```
/
├── index.html          # Main application
├── README.md          # This file
└── LICENSE           # MIT License
```

## License

MIT - Built for the Bitcoin and Stacks ecosystem
