# Xian Network Airdrop Eligibility Checker

This repository contains the Lamden blockchain state snapshot used to determine eligibility for the Xian Network (XIAN) token airdrop.

## Overview

The Xian Network is a new cryptocurrency project based on the Lamden codebase. As part of our launch, we're conducting an airdrop of XIAN tokens to existing Lamden token holders, specifically those holding TAU (Lamden's native currency) and RSWP tokens.

## Repository Contents

- `lamden_state.json`: A snapshot of the Lamden blockchain state that contains all token balances used to determine airdrop eligibility.

## Checking Your Eligibility

To check if you're eligible for the XIAN airdrop, you can search for your Lamden wallet address in the `lamden_state.json` file.

### Steps to Check Eligibility:

1. Open the `lamden_state.json` file
2. Use your text editor's search function (usually Ctrl+F or Cmd+F)
3. Search for your address using the following formats:

#### For TAU token balances:
```
currency.balances:YOURADDRESS
```

#### For RSWP token balances:
```
con_rswp_lst001.balances:YOURADDRESS
```

Replace `YOURADDRESS` with your actual Lamden wallet address.

If either search returns a result, you will see your token balance. However, to be eligible for the XIAN airdrop, your balance must be sufficient to receive at least 1 XIAN after applying the multipliers:
- For TAU: You need at least 100 TAU (100 × 0.01 = 1 XIAN)
- For RSWP: You need at least 10,000 RSWP (10,000 × 0.0001 = 1 XIAN)

The balance shown represents the amount of TAU or RSWP tokens you hold, which will determine your XIAN airdrop allocation.

## About the Xian Network

The Xian Network is a new cryptocurrency project building on the foundation of Lamden's technology. While we are a separate project, we value the existing Lamden community and are offering this airdrop as a way to recognize TAU and RSWP token holders.

## Airdrop Details

The XIAN token is the native currency of the Xian Network. This airdrop is our way of distributing XIAN tokens to the Lamden community as we launch our new project.

### How to Claim Your XIAN Tokens

If you're eligible for the airdrop, follow these steps to claim your XIAN tokens:

1. Download and install the Xian Wallet Chrome extension from the Chrome Web Store:
   [https://chromewebstore.google.com/detail/xian-wallet/kcimjjhplbcgkcnanijkolfillgfanlc](https://chromewebstore.google.com/detail/xian-wallet/kcimjjhplbcgkcnanijkolfillgfanlc)

2. Import your Lamden wallet's private key into the Xian Wallet extension.

3. Visit the official Xian airdrop claiming website:
   [https://airdrops.xian.org](https://airdrops.xian.org)

4. Connect your Xian Chrome wallet to the website.

5. Claim your XIAN tokens.

### Airdrop Calculation

Your XIAN airdrop amount is calculated based on your TAU and RSWP holdings using the following multipliers:

- TAU balance × 0.01
  - Example: 100,000 TAU = 1,000 XIAN
- RSWP balance × 0.0001
  - Example: 1,000,000 RSWP = 100 XIAN

### Airdrop Limits

- Minimum XIAN airdrop: 1 XIAN (after multiplier)
- Maximum XIAN airdrop: 10,000 XIAN (after multiplier)

Note that the maximum cap applies to the calculated amount. For example, if you hold 1,000,000 TAU, your calculated amount would be 10,000 XIAN (the maximum). Any amount beyond this will not increase your airdrop allocation.

## Questions or Issues

If you have any questions about the airdrop eligibility or are experiencing issues with checking your balance, please open an issue in this repository or contact our team through our official channels.
