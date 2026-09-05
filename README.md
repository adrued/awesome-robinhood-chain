# Awesome Robinhood Chain [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

> A curated list of the Robinhood Chain ecosystem — tokenized stocks, DeFi, oracles, tooling, and autonomous agents.

[Robinhood Chain](https://robinhood.com) is an Ethereum Layer-2 (Arbitrum Orbit) built for real-world assets. It moves tokenized US stocks and ETFs on-chain and makes them tradable 24/7. This list tracks the projects, infra, and tools building on it.

**Maturity tags:** `[live]` in production · `[beta]` public but early · `[experimental]` moving fast.

## Contents

- [Infrastructure](#infrastructure)
- [DEXs & Liquidity](#dexs--liquidity)
- [Oracles & Data](#oracles--data)
- [Wallets & Custody](#wallets--custody)
- [Developer Tooling](#developer-tooling)
- [Agents & Automation](#agents--automation)
- [Docs & Learning](#docs--learning)

## Infrastructure

- `[live]` **[Arbitrum Orbit](https://arbitrum.io/orbit)** — the L2 stack Robinhood Chain is built on.
- `[live]` **[Robinhood Chain RPC](https://robinhood.com)** — public JSON-RPC for reads and transactions.
- `[live]` **Stock Tokens** — tokenized equities (NVDA, AAPL, GOOG…) as ERC-20s with 24/7 markets.

## DEXs & Liquidity

- `[live]` **[Uniswap](https://uniswap.org)** — live on Robinhood Chain from day one.
- `[live]` **[1inch](https://1inch.io)** — DEX aggregator routing across pools.
- `[beta]` **[Lighter](https://lighter.xyz)** — orderbook-style trading for Stock Tokens.

## Oracles & Data

- `[live]` **[Chainlink](https://chain.link)** — the canonical price oracle for Robinhood Chain.
- `[live]` **[Trust Me Capital](https://capital.devfridge.cool/)** — TMC token analytics and Trust Rewards time-lock membership with non-transferable points on Robinhood Chain.
- `[beta]` **On-chain NAV feeds** — continuous mark prices for tokenized equities.

## Wallets & Custody

- `[live]` **[BitGo](https://bitgo.com)** — institutional custody for the ecosystem.
- `[live]` **[Alchemy](https://alchemy.com)** — infra and account tooling.

## Developer Tooling

- `[live]` **[viem](https://viem.sh)** — typed client that talks to Robinhood Chain out of the box.
- `[beta]` **[Foundry](https://getfoundry.sh)** — deploy and test Orbit contracts.

## Agents & Automation

- `[beta]` **[Bastion](https://github.com/adrydevel/bastion)** — autonomous, verifiable AI fund. A swarm of agents (running on [Nous Research](https://nousresearch.com) Hermes) trades tokenized stocks and anchors a proof of every decision on-chain.
- `[experimental]` **Keeper bots** — recurring-buy and rebalance automation for Stock Tokens.

## Docs & Learning

- **[Robinhood Chain overview](https://robinhood.com)** — official announcement and docs.
- **[Chainlink on Orbit](https://docs.chain.link)** — integrating the oracle.

## Contributing

Contributions welcome — see [CONTRIBUTING.md](CONTRIBUTING.md). Keep entries factual, one line, with a maturity tag.

## License

[![CC BY 4.0](https://licensebuttons.net/l/by/4.0/88x31.png)](https://creativecommons.org/licenses/by/4.0/)
<!-- curated by adrydevel -->
