---
title: "FindThePump"
date: 2025-07-03
summary: "A fast monitoring tool that tracks PumpFun token transactions using gRPC streaming to identify high volume tokens pre-bonding."
tags: ["gRPC", "Solana", "Node", "blockchain", "Pump.fun", "Discord"]
---

## What is FindThePump?

This application monitors buy and sell transactions on the PumpFun platform in real-time using gRPC streaming, highlighting tokens with high volume across multiple time windows.

## Why I Built It

I built this tool to try and identify Pumpfun tokens with high trading volume early.  Here's what it does:

- **Real-time Monitoring**: Continuously watches the Solana blockchain for new PumpFun buy/sell transactions
- **Transaction Tracking**: Identifies and logs every buy and sell transaction as it happens
- **Volume Analysis**: Tracks how much NET SOL is being spent on each token
- **User Activity**: Monitors which wallets are buying and selling tokens, looking for unique wallet counts
- **Discord Integration**: Can send alerts to Discord when significant activity is detected


## Notes 

If I were to continue working on this I would want to add the following functionality:

-  Add support for additional launchpads such as bonk.fun
-  Use a database backend for storage
-  Identify/Filter bot transactions ( ie buy/sell in the same transaction)

## Code & Deployment

📦 [GitHub Repository](https://github.com/dmittakarin8/findThePump)

🛠️ Follow the README for setup instructions.

<!-- Add screenshots or diagrams here when available --> 