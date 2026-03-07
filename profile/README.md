# FabricBloc

**Web3 infrastructure that fits in your pocket.**

Wallets, payments, and smart contracts — embedded directly into mobile apps. No browser extensions. No seed phrases. No friction. Just Ethereum, running natively where your users already are.

---

### What We're Building

```
Your App
  └── FabricKit (Swift SDK)
        ├── Embedded Wallets     → non-custodial, created in-app
        ├── Stablecoin Payments  → USDC send/receive, gas-free
        ├── Smart Contracts      → deploy & interact via API
        ├── NFTs & Tokens        → ERC-721, ERC-1155, ERC-20
        └── Transaction Engine   → batching, sponsorship, orchestration
```

### EVM-First

Ethereum is home. We build on the EVM and extend across L2s.

`Ethereum` | `Polygon` | `Arbitrum` | `Base` | `BNB Chain` | `Avalanche`

### Mobile-First

**[FabricKit](https://github.com/FabricBloc/FabricKit)** — our Swift SDK for iOS and macOS. Android coming soon.

```swift
import FabricKit

let wallet = try await FabricBloc.wallets.create(
    userId: "user_123",
    type: .nonCustodial,
    chains: [.ethereum, .polygon]
)

// wallet.address -> 0x...
// No external apps. No popups. Just works.
```

### SDKs

| Package | Platform | Status |
|---------|----------|--------|
| [`FabricKit`](https://github.com/FabricBloc/FabricKit) | Swift — iOS / macOS | Active |
| [`fabricbloc-ts`](https://github.com/FabricBloc/fabricbloc-ts) | TypeScript / Node.js | Active |
| [`fabricbloc-python`](https://github.com/FabricBloc/fabricbloc-python) | Python | Active |
| Android SDK | Kotlin | Coming Soon |

### Links

**Docs** — [docs.fabricbloc.com](https://docs.fabricbloc.com) | **API** — [docs.fabricbloc.com/api](https://docs.fabricbloc.com/api) | **Website** — [fabricbloc.com](https://fabricbloc.com)

---

Built by [BlocLabs](https://bloclabs.com) — blockchain engineering for companies that ship.
