---
title: "X Tracker"
date: 2025-06-29
summary: "A lightweight terminal app that monitors X (Twitter) follow activity in real time and sends alerts via Discord or Telegram."
tags: ["Go", "Bubble Tea", "SQLite", "API", "CLI", "Monitoring", "X"]
---

<!-- Project content will go here -->

## What is X Tracker?


**X Tracker** is a terminal-based tool that monitors follow/unfollow activity for selected X (Twitter) accounts in real time. It is lightweight and can run on a low-cost VPS.  The code is built for a specific RapidAPI plan and will need to be modified to accomodate a different set of API endpoints.  I also added discord/telegram notifications. 

---

## Why I Built It

I'm a blockchain enthusiast and X is the place for "alpha".  I wanted to monitor what projects/accounts my targeted accounts were following so that I could do further research.  Many X tracking apps including X's own API are very expensive.  I needed something simple / lightweight / cheap.  I've been able to run this with no downtime on a $3/month vps with a $20/month RapidAPI plan.  

---

## Code & Deployment

📦 [GitHub Repository](https://github.com/dmittakarin8/x-tracker)

🛠️ Follow the README for setup instructions.

{{< figure src="x-tracker-screenshot-main.png" alt="main" >}}
{{< figure src="x-tracker-screenshot-add.png" alt="add" >}}
