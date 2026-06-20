# NEAR Wallet Tracker Skill

## Problem It Solves
NEAR users have no easy way to track and understand their on-chain activity without manually checking block explorers. This skill automates wallet monitoring and delivers categorized transaction summaries.

## Skill Name
near-wallet-tracker v1.0.0

## Features
- Connect to any NEAR wallet address
- Fetch recent transactions via NEAR RPC
- Auto-categorize as Send, Receive, Swap, or Stake
- Generate weekly summary reports
- Monitor balance changes

## Commands
- near-wallet-connect [wallet.near] — Connect wallet
- near-wallet-txns — Fetch and categorize transactions
- near-wallet-report — Generate weekly report
- near-wallet-balance — Check current balance
- near-wallet-history [limit] — View transaction history

## Live Test Result
Tested on maiye.near — fetched 25 real transactions, balance 166.90 NEAR, categories: Send, Receive, Swap confirmed working.

## Implementation
Full Python code: near-wallet-tracker/implementation.py
RPC: https://rpc.mainnet.near.org
