# 🪙 Solana Token DApp

A decentralized application (DApp) built with React + TypeScript + Vite for interacting with Solana tokens. Users can connect their wallets, view balances, and send SPL tokens on the Solana blockchain.

---

## 🚀 Features

- 🔐 Connect Phantom Wallet
- 💰 View wallet balance
- ✉️ Send SPL tokens
- 🧠 Built using `@solana/web3.js`
- ⚡ Fast and modern frontend with **React + Vite**
- 🌐 Hosted with full support for Web3 integration

---

## 🛠️ Tech Stack

| Technology        | Description                                |
|-------------------|--------------------------------------------|
| React             | Frontend UI framework                      |
| Vite              | Fast dev server and build tool             |
| TypeScript        | Type-safe JavaScript                       |
| Solana Web3.js    | Solana blockchain interaction              |
| Buffer (Polyfill) | Node's `Buffer` polyfill for browser       |
| Phantom Wallet    | Solana wallet for user connection          |

---

## 📦 Installation

> Clone the repo and install dependencies:

```bash
git clone https://github.com/sania102/solana-token-dapp.git
cd solana-token-dapp
npm install
⚙️ Development Setup
bash
Copy
Edit
# Start the local dev server
npm run dev
Open http://localhost:5173 in your browser

Make sure you have the Phantom Wallet extension installed

🏗️ Build for Production
bash
Copy
Edit
npm run build
This will generate a dist/ folder with the production build of your DApp.

🧪 Project Structure
bash
Copy
Edit
solana-token-dapp/
├── src/
│   ├── App.tsx               # Main App component
│   ├── main.tsx              # Entry point
│   ├── wallet/               # Wallet connection logic
│   └── utils/                # Helper functions
├── vite.config.ts            # Vite config with plugins
├── tsconfig.json             # TypeScript configuration
└── package.json              # Project dependencies
🔐 Wallet Integration
This DApp uses the Phantom wallet for transaction signing and balance viewing.

📥 To Connect:
Install Phantom Wallet

Click "Connect Wallet" in the app

Approve connection in the Phantom popup

🔧 Common Issues
🐛 Buffer is not defined?
Add this in main.tsx:

ts
Copy
Edit
import { Buffer } from 'buffer';
window.Buffer = Buffer;
And install it if not installed:

bash
Copy
Edit
npm install buffer
📚 Learn More
Solana Web3.js Docs

Phantom Wallet

Vite

React

👩‍💻 Author
Made with by Sania102

📜 License
This project is licensed under the MIT License — see the LICENSE file for details.

