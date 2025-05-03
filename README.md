# VLayer Web Proof - Twitter Ownership Verification

This project demonstrates the use of **Web Proof** functionality on the VLayer testnet. It leverages the VLayer infrastructure to verify ownership of a Twitter account through cryptographic proofs.

## ✨ Features

- ✅ Verifies Twitter account ownership using VLayer's notary services
- 🧪 Includes smart contracts for the prover and verifier
- 🧰 Simple CLI-based flow using Foundry, Bun, and VLayer CLI
- 🌐 Hosted UI (optional) for interacting with the proof system

## 🛠️ Tech Stack

- Solidity (Foundry)
- Bun (for scripting and CLI interaction)
- VLayer SDK
- Optimism Sepolia Testnet
- TypeScript + React (for optional frontend)

## 🔄 Setup & Run

### 1. Clone and Install

```bash
git clone https://github.com/RIKSON93/myvlayer-web-proof.git
cd myvlayer-web-proof
bun install
```

### 2. Configure

Update `.env.testnet.local` with the appropriate values, including:
- Your Twitter handle
- Your wallet address
- Notary public key

### 3. Prove

```bash
bun run prove
```

### 4. Verify (Smart Contract)

Deploy and interact with `WebProofVerifier.sol` using Foundry or any EVM-compatible environment.

## 📄 Smart Contracts

Located under `src/vlayer/`:
- `WebProofProver.sol`
- `WebProofVerifier.sol`

## ✅ Test

```bash
forge test
```

## 🧠 Concept

This proof system establishes a trustless link between a wallet address and a Twitter account using cryptographic notaries and VLayer verification infrastructure.

---

Made with ❤️ for the **VLayer Proof of Innovation** contest.