<div align="center">
  <img src="https://raw.githubusercontent.com/roguesignalchain/.github/main/assets/twitter_cover.png" alt="Rogue Signal (ROGUE) Banner" width="100%" />

  <br/><br/>

  [![Chain ID](https://img.shields.io/badge/CHAIN_ID-800055-000000?style=for-the-badge&logoColor=white&labelColor=18181b)](https://docs.roguechain.org)
  [![Consensus](https://img.shields.io/badge/CONSENSUS-RandomX_%5Brx%2F0%5D-000000?style=for-the-badge&logoColor=white&labelColor=18181b)](https://docs.roguechain.org/consensus/randomx)
  [![Difficulty](https://img.shields.io/badge/DIFFICULTY-LWMA--1_%5BN%3D60%5D-000000?style=for-the-badge&logoColor=white&labelColor=18181b)](https://docs.roguechain.org)
  [![Target](https://img.shields.io/badge/BLOCK_TIME-30s-000000?style=for-the-badge&logoColor=white&labelColor=18181b)](https://docs.roguechain.org)
  [![Supply](https://img.shields.io/badge/MAX_SUPPLY-100%2C000%2C000_ROGUE-000000?style=for-the-badge&logoColor=white&labelColor=18181b)](https://roguechain.org)
  [![EVM Compatible](https://img.shields.io/badge/VM-EVM_COMPATIBLE-000000?style=for-the-badge&logoColor=white&labelColor=18181b)](https://docs.roguechain.org)

  <br/>

  <h3><code>[SOVEREIGN CPU-ONLY PROOF-OF-WORK EVM BLOCKCHAIN]</code></h3>
  <p><b>Fair-launch, ASIC-resistant Layer-1 smart contract execution environment secured purely by consumer CPUs.</b></p>

  <p>
    <a href="https://roguechain.org"><b>Website</b></a> •
    <a href="https://docs.roguechain.org"><b>Documentation</b></a> •
    <a href="https://x.com/roguesignal_"><b>X / Twitter</b></a> •
    <a href="https://discord.gg/c6bwF6Wk6c"><b>Discord</b></a>
  </p>
</div>

---

### 📡 Network Specifications & Telemetry

```ini
[ROGUE SIGNAL TELEMETRY HUD]
Network Name        = Rogue Signal
Currency Ticker     = ROGUE
Chain ID            = 800055
Consensus Engine    = RandomX (rx/0 profile, full-node solo mining)
Block Time Target   = 30 seconds
Difficulty Rule     = LWMA-1 (N=60 blocks, +-33% clamp)
Initial Reward      = 24 ROGUE per block
Halving Interval    = 2,100,000 blocks (~2 years)
Reward Split        = 95% Miner (22.8 ROGUE) / 5% Protocol Treasury (1.2 ROGUE)
Supply Cap          = 100,000,000 ROGUE (Hard cap, zero tail emission)
Anti-51% Finality   = MaxReorgDepth 90 blocks (~45m) + ECBP-1100 (MESS)
Seed Rotation       = Every 2048 blocks (~17.07h) with 64-block (~32m) lag
Validation Bounds   = Strict MTP-11 + 15s future drift + 64B max ExtraData
Genesis Block Hash  = 0xc6f7f29d6a23f1921f3e514401a82a60ffa1f21885497dbf6414e8bb2f22b91d
```

---

### ⚡ Core Repositories & Ecosystem

| Repository | Description | Status |
| :--- | :--- | :---: |
| [`rogue-core-chain`](https://github.com/roguesignalchain/rogue-core-chain) | Core Go/C++ blockchain daemon (`core-rogue`), native RandomX consensus, LWMA-1 engine & integrated CPU miner. | `Active` |
| [`rogue-desktop-client`](https://github.com/roguesignalchain/rogue-desktop-client) | High-contrast tactical desktop GUI wallet & 1-click miner manager powered by Tauri v2 and Rust. | `Active` |
| [`rogue-chain-docs`](https://github.com/roguesignalchain/rogue-chain-docs) | Official developer documentation, architecture specifications, API references & brand guide. | `Active` |
| [`rogue-main-website`](https://github.com/roguesignalchain/rogue-main-website) | Official public web portal, live network status and ecosystem launchpad. | `Active` |

---

### 💻 Quickstart: Build & Run a Node

Run a native Rogue Signal node and begin mining with your CPU:

```bash
# Clone the core repository with submodules (RandomX engine)
git clone https://github.com/roguesignalchain/rogue-core-chain.git --recurse-submodules
cd rogue-core-chain

# Build the core-rogue binary natively
./scripts/build-core.sh

# Launch node and join the network
./build/bin/core-rogue --rogue --http --http.api eth,net,web3

# Or mine with your local CPU threads
./build/bin/core-rogue --rogue --mine --miner.threads 4 --miner.etherbase 0xYourWalletAddress
```

---

### 🛡️ Cypherpunk Principles

* **ASIC/FPGA Immunity:** Democratized consensus through memory-hard cryptographic puzzles optimized strictly for consumer CPU hardware cache.
* **No Premine, No ICO, No VCs:** 100% fair launch emission. Every ROGUE token in existence must be computed block by block.
* **Zero Shared-Library Bloat:** Statically linked, high-performance C++20 RandomX engine embedded into a hardened Ethereum Virtual Machine.

---

<div align="center">
  <sub>"Sovereignty is not granted. It is computed."</sub><br/>
  <b>ROGUE SIGNAL PROTOCOL • CHAIN ID 800055</b>
</div>

