# GIWA Deposit Bridge

A deposit-only bridge for moving ETH from **Ethereum Sepolia** to **GIWA Sepolia** (GIWA Chain testnet, chain ID 91342).

Open the page, connect your wallet, and deposit. Deposits land in about 1–3 minutes.

## What it does

- Live Sepolia and GIWA Sepolia block heights and wallet balances
- Deposit ETH from Ethereum Sepolia (chain 11155111) to GIWA Sepolia (chain 91342) through the official OptimismPortal contract
- Quick amounts, optional different recipient, and a 3-step progress tracker that watches your GIWA balance for the arrival
- Paste-a-hash deposit checker and a session deposit log
- Add-GIWA / Switch-to-Sepolia wallet buttons, official contract list, and FAQ

## What it does not do

Withdrawals are out of scope. GIWA withdrawals go through the OP Stack challenge period (about 7 days) and belong in a full bridge.

## Contracts

- OptimismPortal (Sepolia): `0x956962C34687A954e611A83619ABaA37Ce6bC78A`
- L1StandardBridge (Sepolia): `0x77b2ffc0F57598cAe1DB76cb398059cF5d10A7E7`
- L2ToL1MessagePasser (GIWA Sepolia): `0x4200000000000000000000000000000000000016`

## Testnet only

GIWA mainnet is still under development. Everything here is testnet ETH with no monetary value. Never send mainnet assets to these contracts.
