# EVM Projects

**Languages:** Solidity, JavaScript, Node.js

**Networks**: EVM Compatible

EVM stands for Ethereum Virtual Machine — the core component that runs smart contracts on Ethereum and many compatible blockchains.

EVM-compatible networks include:
- Ethereum Mainnet
- Binance Smart Chain (BNB Chain)
- Polygon (Matic)
- Arbitrum
- Optimism
- Avalanche C-Chain

---

## 📚 Projects Overview

---

### 🔹 [EVM\_ERC20\_Upgradeable](https://github.com/cmd-ctl/EVM_ERC20_Upgradeable)

Upgradeable ERC20 token with:

* UUPSUpgradeable pattern (ERC1967Proxy)
* Role-based access (MODERATOR, ACCOUNTANT, OWNER)
* Blacklist system
* MaxSupply control with fix
* Emergency pause
* AdminBurn for blacklisted addresses
* Upgradeable to future versions

---

### 🔹 [EVM\_ERC20Tokens](https://github.com/cmd-ctl/EVM_ERC20Tokens)

Collection of ERC20 token examples:

* Basic ERC20 (mint, burn)
* ERC20 with fees
* ERC20 with claim mechanism
* ERC20 with time-locks
* On-chain claim logic for users

---

### 🔹 [EVM\_NativeToken-Sender](https://github.com/cmd-ctl/EVM_NativeToken-Sender)

**Node.js Script** to bulk-send native tokens (ETH, BNB, MATIC, etc.):

* Reads recipient list from file
* Sends tokens from single wallet
* Shows progress, TX hashes, errors
* Configurable parameters
* Useful for airdrops, distributions

Full 📖 [Documentation here](https://github.com/cmd-ctl/EVM_NativeToken-Sender#readme)

---

### 🔹 [EVM\_NFT\_HolderDistribution\_Staking](https://github.com/cmd-ctl/EVM_NFT_HolderDistribution_Staking)

**NFT ecosystem contracts**:

- ERC721A NFT with:
- HolderDistribution contract:
  * Distribute ERC20 or native token to NFT holders
  * Supports manual and automated distributions
  * Emergency withdrawal
- NFTStaking contract:
  * Stake NFT to earn ERC20 rewards
  * One active stake per wallet
  * Adjustable staking time
  * Emergency unstake
  * Full visibility on reward state

---

## 🛠 Tech Stack

* Solidity ^0.8.x
* Node.js v16+

---

## ⚠️ Disclaimer

All contracts provided as educational samples.
**Use at your own risk.**
