# CrossSwap

A DeFi web interface for the CrossFi network, based on the open-source PancakeSwap frontend.

Built for the DoraHacks CrossFi hackathon (2024): [project page](https://dorahacks.io/build/15933) · Community: [Telegram](https://t.me/crossfigodcom)

## About

CrossSwap is a fork of [pancakeswap/pancake-frontend](https://github.com/pancakeswap/pancake-frontend). It keeps the upstream monorepo structure (web app, SDK packages, UI kit) and adapts it as the interface layer for a CrossFi DEX.

Related repository with the CFG token, tests, deployment script and whitepaper: [CROSSFIGOD-DEFI-V3](https://github.com/Godblessmylife/CROSSFIGOD-DEFI-V3).

## Credits and license

This project is a derivative of the PancakeSwap frontend and is released under the [GNU General Public License v3.0](./LICENSE), the same license as the upstream project. Copyright and attribution notices from upstream are kept. Many package names and descriptions below come from upstream.

## Changes from upstream

<!--
List what you changed or added for CrossFi, one line each. For example:
- CrossFi chain configuration (chain ID, RPC, explorer)
- Branding, logo and texts
- Token lists for CrossFi
- Anything else you actually modified
-->

## Repository structure

| Path | Description |
| --- | --- |
| `apps/web` | Main DEX web application |
| `apps/aptos` | Aptos application |
| `apps/blog` | Blog |
| `apps/bridge` | Bridge |
| `apps/games` | Games |
| `apps/e2e` | End-to-end tests |
| `packages/*` | Shared SDKs, hooks, UI kit and configuration |

## Getting started

Requirements: [pnpm](https://pnpm.io) 8.

```sh
pnpm install
```

### `apps/web`

```sh
# development server
pnpm dev

# production
