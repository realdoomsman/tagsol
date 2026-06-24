<div align="center">

# ◆ tagsol

### Send SOL to @names, not addresses.

[![Live](https://img.shields.io/badge/Live-tagsol.xyz-white?style=for-the-badge&logo=vercel&logoColor=black)](https://tagsol.xyz)
[![Twitter](https://img.shields.io/badge/@TagSolxyz-black?style=for-the-badge&logo=x&logoColor=white)](https://x.com/TagSolxyz)
[![Solana](https://img.shields.io/badge/Solana-black?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjAiIGhlaWdodD0iMjAiIHZpZXdCb3g9IjAgMCAyMCAyMCIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj48Y2lyY2xlIGN4PSIxMCIgY3k9IjEwIiByPSIxMCIgZmlsbD0id2hpdGUiLz48L3N2Zz4=)](https://solana.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-white?style=for-the-badge)](LICENSE)

<br />

**Register a human-readable @name for your Solana wallet.**<br />
Instead of sharing `7xK2mF9qR4nP8vL...`, just share `@yourname`.

<br />

[Live App](https://tagsol.xyz) · [Twitter](https://x.com/TagSolxyz) · [Report Bug](https://github.com/realdoomsman/tagsol/issues)

---

</div>

<br />

## ✦ Features

| Feature | Description |
|---------|-------------|
| **@Name Registration** | Claim a unique handle linked to your Solana wallet — free to register |
| **Instant Lookup** | Search any @name to reveal the linked wallet address + on-chain stats |
| **Send SOL** | Send SOL directly to @names via Phantom wallet or manual transfer |
| **Profile Pages** | Every registered name gets a shareable profile at `tagsol.xyz/@name` |
| **Vanity Wallets** | Generate custom-prefix Solana keypairs directly in your browser |

<br />

## ✦ Architecture

```
tagsol/
├── programs/             # Solana smart contract (Anchor/Rust)
│   └── alias-registry/   # On-chain alias registry program
├── api/                  # REST API server (Express + Supabase)
├── web/                  # Frontend (React + Vite)
├── tests/                # Anchor integration tests
└── vercel.json           # Deployment config
```

<br />

## ✦ Tech Stack

| Layer | Technology |
|-------|-----------|
| **Smart Contract** | Rust · Anchor Framework |
| **Frontend** | React · TypeScript · Vite |
| **Backend** | Express · Supabase |
| **Blockchain** | Solana · @solana/web3.js |
| **Hosting** | Vercel |

<br />

## ✦ Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) 18+
- [Rust](https://rustup.rs/) & [Anchor CLI](https://www.anchor-lang.com/) (for smart contract development)
- [Solana CLI](https://docs.solana.com/cli/install-solana-cli-tools) (optional)

### Run the Frontend

```bash
cd web
npm install
npm run dev
```

App runs at `http://localhost:5173`

### Run the API

```bash
cd api
cp .env.example .env    # configure your keys
npm install
npm run dev
```

API runs at `http://localhost:3001`

### Build the Smart Contract

```bash
anchor build
anchor test
```

<br />

## ✦ Token

| | |
|---|---|
| **Ticker** | $TAG |
| **Contract Address** | `TPBZ4LBaDZ4CRKCi6oFurrJeLqA8eRiG4DzNoKepump` |
| **Network** | Solana |

<br />

## ✦ Links

- 🌐 **Website** — [tagsol.xyz](https://tagsol.xyz)
- 𝕏 **Twitter** — [@TagSolxyz](https://x.com/TagSolxyz)

<br />

## ✦ License

[MIT](LICENSE)

<div align="center">
<br />
<sub>Built on Solana ◆</sub>
</div>
