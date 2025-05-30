# ⏳ Stellar TimeLock Transaction

This repository demonstrates how to create and submit **time-locked transactions** on the Stellar blockchain. Time-locked transactions are useful when you want funds to be accessible only after a certain time or ledger sequence number.

---

## 📌 What is TimeLock on Stellar?

Stellar does not use smart contracts in the same way as Ethereum or Solana. Instead, you can build powerful logic using:

- **Pre-signed transactions**
- **Time bounds (minTime, maxTime)**
- **Multi-signature accounts**

This project demonstrates how to use these features to lock funds until a certain time.

---

## 📁 Project Structure


stellar-timelock/
- generate_account.js # Creates accounts for demo
- timelock_create.js # Creates a time-locked transaction
- timelock_submit.js # Submits the transaction after unlock time
- .env # Environment variables for secret keys
- README.md # Project info

---

## ⚙️ Requirements

- Node.js 16+
- npm
- [Stellar SDK for JS](https://github.com/stellar/js-stellar-sdk)

---

## 🛠️ Setup

```bash
git clone https://github.com/yourusername/stellar-timelock.git
cd stellar-timelock
npm install
