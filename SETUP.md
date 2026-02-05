# Technical Setup - Psychedelic Agent Protocol

## ✅ Completed Setup (2026-02-05)

### 1. Monad Wallet (Keystore)

**Address:** `0x6B3c6c0Bf46246823EF9cF4eBa5032F3A6fa9d3C`

**Keystore Details:**
- Location: `~/.foundry/keystores/claude-monad`
- Password: `~/.monad-keystore-password` (chmod 600)
- Created: 2026-02-05 00:42 UTC

**Security:**
- Encrypted keystore on disk
- Auto-generated password (32 bytes, base64)
- Will be used for Safe multisig (2-of-3) deployments
- Claude signs (1/2), user approves (2/2)

### 2. Testnet Funding

**Faucet Transaction:** `0xbf140a0286f4734d7475d7a68729e49e93f400d3436c8cb074f723441e784dc2`

**Balance:** 1.0 MON (Monad Testnet)

**Faucet API:** `https://agents.devnads.com/v1/faucet`
- Chain ID: 10143
- Response time: ~2-3 seconds
- Amount: 1 MON per request

### 3. Foundry Installation

**Version:** 1.5.1-stable (b0a9dd9ced 2025-12-22)

**Binaries:**
- `forge` ✅
- `cast` ✅
- `anvil` ✅
- `chisel` ✅

**Installation Path:** `~/.foundry/bin`

### 4. Monad Development Skill

**Status:** ✅ Verified and ready

**Features:**
- Safe multisig deployments (2-of-3)
- Testnet faucet integration
- Contract verification API (3 explorers)
- Foundry + Prague EVM
- Never asks for user's private key

**Skill Location:** `/home/kukulcan/.nvm/versions/node/v24.13.0/lib/node_modules/openclaw/skills/monad-development/`

### 5. GitHub Repository

**Repo:** https://github.com/kukulcanxyz/psychedelic-agent-protocol

**Status:** Public, initialized
- Initial commit: c3c495f
- Remote: origin/master
- Branch tracking enabled

---

## Network Configuration

**Monad Testnet:**
- Chain ID: 10143
- RPC: https://testnet-rpc.monad.xyz
- Faucet: https://agents.devnads.com/v1/faucet
- Verification: https://agents.devnads.com/v1/verify

**Explorers:**
- MonadVision: https://testnet.monadvision.com
- Socialscan: https://monad-testnet.socialscan.io
- Monadscan: https://testnet.monadscan.com

---

## Next Steps

- [ ] Deploy Safe multisig (2-of-3)
- [ ] Deploy $TRIP token on nad.fun
- [ ] Mint first psychedelic NFTs
- [ ] Deploy skill engine contracts
- [ ] Build marketplace frontend

---

_Setup completed in parallel with frontend development (Claude Code: session tidy-lagoon)_
