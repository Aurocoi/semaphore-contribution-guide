# semaphore-contribution-guide
“Beginner-friendly guide and setup for contributing to the Semaphore Binary Merkle Root Fix ceremony.”
semaphore-phase2-guide/
│── README.md        # Full beginner-friendly guide
│── setup.sh         # Shell script with all commands
│── screenshots/     # (Optional) screenshots of steps
│── LICENSE          # MIT License (open source)
# 🚀 Semaphore Trusted Setup Contribution (Beginner Guide)

This repo explains step by step how to contribute to the **Semaphore Binary Merkle Root Fix** trusted setup ceremony using `phase2cli`.  

Semaphore is a **zero-knowledge protocol** that lets people prove membership in a group **without revealing their identity**. By contributing, you help ensure its security and decentralization.

---

## 🔧 Prerequisites

- A GitHub Codespace, VPS, or Ubuntu machine
- Git installed
- Node.js (>= 18)
- Basic terminal knowledge (copy-paste commands works fine!)

---

## ⚡ Setup & Contribution Steps

1️⃣ **Update your system**
```bash
sudo apt update && sudo apt upgrade -y
sudo apt install screen -y
git clone https://github.com/privacy-scaling-explorations/phase2cli
cd phase2cli
npm install -g
phase2cli contribute
screen -S semaphore
phase2cli contribute
