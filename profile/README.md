# FabricBloc

**Embedded wallet and stablecoin infrastructure for mobile apps.**

FabricBloc gives developers the APIs and SDKs to add wallets, USDC payments, and onchain transactions directly inside their applications. No external wallet apps, no seed phrases, no gas fees for users.

---

### Core Infrastructure

| Component | Description |
|-----------|-------------|
| **Embedded Wallets** | Custodial and non-custodial wallets created inside your app |
| **Stablecoin Rails** | USDC-first payment orchestration and settlement |
| **Gas Sponsorship** | Abstract network fees — users never hold ETH |
| **Transaction Engine** | Multi-chain execution, batching, and policy management |
| **Mobile SDKs** | Native components for iOS, Android, and web |
| **NFT & Token Factory** | Deploy ERC-721, ERC-1155, and ERC-20 contracts via API |

### Chains

Base (primary) | Ethereum | Polygon | Arbitrum | BNB Chain | Avalanche

### Get Started

```bash
npm install @fabricbloc/sdk
```

```typescript
import { FabricBloc } from '@fabricbloc/sdk';

const wallet = await fabricbloc.wallets.create({
  userId: "user_123",
  type: "non-custodial",
  chains: ["base", "polygon"],
});
```

### Links

- **Documentation** — [docs.fabricbloc.com](https://docs.fabricbloc.com)
- **API Reference** — [docs.fabricbloc.com/api](https://docs.fabricbloc.com/api)
- **Website** — [fabricbloc.com](https://fabricbloc.com)
- **Status** — [status.fabricbloc.com](https://status.fabricbloc.com)

### SDKs

| Package | Language |
|---------|----------|
| [`fabricbloc-ts`](https://github.com/FabricBloc/fabricbloc-ts) | TypeScript / Node.js |
| [`fabricbloc-python`](https://github.com/FabricBloc/fabricbloc-python) | Python |
| [`FabricKit`](https://github.com/FabricBloc/FabricKit) | Swift (iOS / macOS) |

---

Built by [BlocLabs](https://bloclabs.com)
