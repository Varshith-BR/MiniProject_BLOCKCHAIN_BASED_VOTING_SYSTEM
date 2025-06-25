# 🗳️ Blockchain Based Voting System

## 📘 Overview

This project implements a decentralized, blockchain-based voting platform using **Ethereum smart contracts**. It ensures **voter privacy**, **transparency**, and **security**, while maintaining low infrastructure costs. The system utilizes the Ethereum blockchain to perform user registration, vote casting, and real-time result tracking.

> ⚙️ Deployed and tested on a local Ethereum network using **Ganache**, with MetaMask integration for user interaction.

---

## 👨‍💻 Author
**Varshith B R**

---

## 📦 Prerequisites

Ensure the following tools are installed before proceeding:

| Tool         | Purpose                              | Download Link                             |
|--------------|---------------------------------------|--------------------------------------------|
| Node.js      | JavaScript runtime environment        | https://nodejs.org/                        |
| Ganache      | Local Ethereum blockchain emulator    | https://trufflesuite.com/ganache/         |
| MetaMask     | Browser-based Ethereum wallet         | https://metamask.io/                       |
| Truffle      | Smart contract development framework  | `npm install -g truffle`                  |

---

## 🚀 Setup Instructions

### 1️⃣ Start Ganache

- Launch **Ganache**.
- Click on **"Quickstart Ethereum"** to spin up a local blockchain.
- Note down the RPC URL (usually `http://127.0.0.1:7545`) and Chain ID (typically `1337` or `5777`).

---

### 2️⃣ Configure MetaMask to Connect with Ganache

1. Open the MetaMask extension in your browser (preferably Chrome).
2. Click the **Network dropdown** > **"Add Network"**.
3. Fill in the details:
   - **Network Name:** `Ganache Localhost`
   - **New RPC URL:** `http://127.0.0.1:7545`
   - **Chain ID:** `1337`
   - **Currency Symbol:** `ETH`
4. Click **Save** and **switch to this network**.

---

### 3️⃣ Import Ganache Account to MetaMask

1. In Ganache, click the **key icon** next to any account to reveal the **private key**.
2. In MetaMask:
   - Go to your profile → **Import Account**
   - Paste the private key
   - Click **Import**

You’ve now connected MetaMask to your local Ethereum network using a Ganache account.

---

## 🛠️ Project Installation

### Step-by-step terminal commands:

```bash
# Clone the project
git clone <repository-url>
cd E-Voting_System_Blockchain

# Install dependencies
npm install

# Compile smart contracts
truffle compile

# Deploy contracts to the local Ganache blockchain
truffle migrate --reset

# Start the development server (usually live-server or similar)
npm start
