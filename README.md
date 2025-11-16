# TaskReward - Decentralized Task Management on Polkadot

![Polkadot](https://img.shields.io/badge/Polkadot-E6007A?style=flat&logo=polkadot)
![Built for Hackathon](https://img.shields.io/badge/Hackathon-2025-blue)

## Overview

TaskReward is a blockchain-based task management system built on Polkadot. Users can create tasks, complete them to earn points, and transfer points to others—all secured by smart contracts on the Westend testnet.

## Live Demo

🌐 **Live Website**: [https://taskrewarddapp.vercel.app]
📜 **Smart Contract**: `5EYCAe51jjfyfej22J3CGq56LmPyNRAKzpG4QkoQkkQNB5e6Z`
🔗 **GitHub**: [https://github.com/Jeevang1-epic/taskreward_dapp.git]

## Features

- ✅ **Create Tasks** - Anyone can create tasks with custom reward points
- ✅ **Complete Tasks** - Earn points by completing available tasks
- ✅ **Transfer Points** - Send points to other users
- ✅ **Real-time Updates** - Instant UI updates
- ✅ **Mobile Responsive** - Works on all devices
- ✅ **Wallet Integration** - Connect with Polkadot wallets

## Tech Stack

**Smart Contract**:
- Rust
- ink! 5.0.0
- Polkadot SDK

**Frontend**:
- HTML5
- CSS3
- Vanilla JavaScript
- No external dependencies

**Network**: Westend Testnet

## Quick Start

1. Open `index.html` in a browser
2. Click "Connect Wallet"
3. Create your first task
4. Complete tasks to earn points
5. Transfer points to friends!

## How It Works

1. **Create Task**: Set description and reward points (1-1000)
2. **Complete Task**: Enter task ID to claim rewards
3. **View Tasks**: See all available and completed tasks
4. **Transfer**: Send your earned points to others

## Smart Contract Functions

- `create_task(description, reward_points)` - Create new task
- `complete_task(task_id)` - Complete task and earn rewards
- `transfer_points(to, amount)` - Transfer points
- `get_balance(account)` - Check points balance
- `get_task(task_id)` - Get task details

## Deployment

**Smart Contract**: Deployed on Westend Testnet
**Frontend**: Deployable to Vercel, Netlify, or GitHub Pages

### Deploy to Vercel:



