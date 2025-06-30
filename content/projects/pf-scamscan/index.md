---
title: "pf-scamscan"
date: 2025-06-29
summary: "A CLI tool that detects new Pump.fun token launches and flags potential scams using real-time image analysis."
repo: "https://github.com/dmittakarin8/pf-scamscan"
draft: false
---

## What is pf-scamscan?

pf-scamscan is a CLI-based tool that tracks new token launches on Pump.fun in real time. It connects to the Solana blockchain WebSockets and detects token creation events as they happen. The tool uses perceptual image hashing to identify duplicate or near-duplicate token images — attempting to avoid low-effort scam tokens. Alerts are sent via Discord with social links, token metadata, and a direct buy link.

## Why I Built It

Thousands of Pump.fun tokens are launched daily and a majority of them are created by devs that reuse token images, names, and don't put the effort into creating socials for the tokens.  I wanted to explore the idea of checking the hash of the token image as they are created against a known hash database as an initial "scam" check.  

## Notes

I originally built this baseline back in January of 2025.  If I were to continue working on this I would explore using a GRPC for the fastest connection to Solana.  I would also want to incorporate other launchpads that have since been created to compete with Pump.fun.  Launchpads such as bonk.fun, moonshot, or boop to name a few.  

## Code & Deployment

📦 [GitHub Repository](https://github.com/dmittakarin8/pf-scamscan)

🛠️ Follow the README for setup instructions.

{{< figure src="pf-scamscan-discordAlert.png" alt="discordAlert" >}}

