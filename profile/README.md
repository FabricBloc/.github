![FabricBloc](https://raw.githubusercontent.com/BloclabsHQ/brand-kit-template/main/assets/images/readme-header.png)


# FabricBloc

**Web3 infrastructure for mobile apps.**

Wallets, payments, and smart contracts — embedded directly into your app. No browser extensions. No seed phrases. No gas fees for users. Non-custodial by default — users own their keys.

---

## What We Build

```
Your App
  └── FabricKit / fabricbloc-ts
        ├── Embedded Wallets     → non-custodial, created in-app
        ├── Payments             → USDC send/receive, gas-sponsored
        ├── Smart Contracts      → deploy & interact via API
        ├── NFTs & Tokens        → ERC-721, ERC-1155, ERC-20 factories
        └── Transaction Engine   → batching, sponsorship, orchestration
```

## Chains

`Base` (primary) | `Ethereum` | `Polygon`

EVM-first. We build on Ethereum and extend across L2s.

---

## SDKs

| Package | Platform | Status |
|---------|----------|--------|
| [`FabricKit`](https://github.com/FabricBloc/FabricKit) | Swift — iOS / macOS | Active |
| [`fabricbloc-ts`](https://github.com/FabricBloc/fabricbloc-ts) | TypeScript / Node.js | Active |
| [`fabricbloc-python`](https://github.com/FabricBloc/fabricbloc-python) | Python | Active |
| Android SDK | Kotlin | Coming Soon |

```swift
import FabricKit

let wallet = try await FabricBloc.wallets.create(
    userId: "user_123",
    type: .nonCustodial,
    chains: [.base, .ethereum]
)
// wallet.address -> 0x...
// No external apps. No popups. Just works.
```

---

## Developer Tools

| Tool | Purpose |
|------|---------|
| [`fabricbloc-mcp`](https://github.com/FabricBloc/fabricbloc-mcp) | MCP server — AI agents interact with FabricBloc APIs |
| [`fabricbloc-docs`](https://docs.fabricbloc.com) | API reference and guides |

---

## Links

**Docs** — [docs.fabricbloc.com](https://docs.fabricbloc.com) | **API** — [docs.fabricbloc.com/api](https://docs.fabricbloc.com/api) | **Website** — [fabricbloc.com](https://fabricbloc.com)

---

Built by [BlocLabs](https://bloclabs.com) — blockchain engineering for companies that ship.
