
# 🌍 GramQuest

**Location-Based Quests & Rewards on the TON Blockchain — Built for Telegram**

GramQuest is a Telegram-first, Web3-powered questing platform where users complete real-world challenges to earn TON tokens and NFTs. No apps, no friction — just scan, explore, and earn directly from Telegram.

<img src="https://github.com/user-attachments/assets/722300e1-770f-4db0-bbe1-33e3507dfded" width="200"/>


---

## 🚀 Features

- **Quest Discovery via QR + GPS**
  Start a quest by scanning real-world QR codes or reaching geofenced locations.

- **Telegram-Native Experience**
  Use bots, mini apps, and wallet integrations without installing anything new.

- **Blockchain Rewards**
  Earn verified NFTs, Jettons, and XP tracked on the TON blockchain.

- **Anti-Cheat Engine**
  Multi-layered spoof protection using behavioral data, location patterns, and challenge timers.

- **Quest Creator Portal**
  Let businesses, event organizers, and communities create and track quests in real time.

---

## 🛠️ Tech Stack

| Layer                | Technologies Used                         |
|---------------------|-------------------------------------------|
| **Frontend**         | Telegram Bot (Node.js + Telegraf), React, Next.js |
| **Backend**          | Node.js, Express, PostgreSQL              |
| **Blockchain**       | TON Smart Contracts (Tact), TON Connect   |
| **Storage**          | PostgreSQL, IPFS                          |
| **External Services**| Google Maps API, QR Code API              |

---

## 📦 Architecture

<img src="https://github.com/user-attachments/assets/064d3d10-0168-4e5d-a97f-27ccad55f8b9" width="420"/>

Key layers:
- **User Layer**: Telegram users, wallets, quest creators
- **Frontend Services**: Bot UI, mini app, reward UI
- **Backend Services**: API gateway, quest engine, location validator
- **Storage**: PostgreSQL, IPFS
- **Blockchain Layer**: Reward contract (via TON)

---

<!-- ## 🧪 Running Locally

```bash
# Clone the repo
git clone https://github.com/yourorg/gramquest.git
cd gramquest

# Install dependencies
npm install

# Run backend
cd backend
npm start

# Run frontend (mini app or dashboard)
cd ../frontend
npm run dev
````

Make sure to configure your `.env` file with API keys and TON wallet secrets.

---

## 🧩 Folder Structure

```
gramquest/
├── backend/              # Node.js API and quest logic
├── frontend/             # React-based Telegram Mini App & Creator Dashboard
├── contracts/            # TON smart contracts (Tact)
├── docs/                 # Architecture diagrams, pitch deck
└── README.md
```

--- -->

## 🤝 Contributing

Contributions welcome! Please:

* Fork the repo
* Create a feature branch
* Open a pull request describing your changes

---

## 📬 Contact

Built for the TON ecosystem by GramQuest Team.
Got ideas, collab requests, or bugs? DM us on Telegram: [@ironicdegawd](https://t.me/ironicdegawd)
