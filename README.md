<div align="center"><img width="100px" src="logo.png"></div>

# Awesome Grin [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of Grin services, softwares and tools.

Pull requests are welcome!

## Content

- [Nodes](#nodes)
- [Wallets](#wallets)
- [Explorers](#explorers)
- [Mining Softwares](#mining-softwares)
- [Mining Pools](#mining-pools)
- [Payment Processors](#payment-processors)
- [Faucet](#faucet)
- [Libraries](#libraries)
- [Other Services](#other-services)


## Nodes

- [Grin](https://github.com/mimblewimble/grin) - Original Grin implementation (cli only).
- [Grin++](https://github.com/GrinPlusPlus/GrinPlusPlus) - Grin node implementation in C++ for Windows/Linux/macOS with GUI.

## Wallets

### Desktop Wallets

- [`grin-wallet`](https://github.com/mimblewimble/grin-wallet) - The original Grin wallet (command line/RPC/REST only).
- [Grin++](https://github.com/GrinPlusPlus/GrinPlusPlus) - Wallet for Windows/Linux/macOS with GUI.
- [Niffler](https://github.com/grinfans/niffler) - Open Source Grin GUI Wallet; support English and 简体中文.
- [Wallet 713](https://github.com/vault713/wallet713) - A command line wallet that integrates with [Grinbox](https://grinbox.io/) and Keybase for easily sending transactions if you can't or don't want to expose your IP-address publicly. It also supports generating proofs that prove you sent a transaction or amount.

### Mobile Wallets

- [Grin++ Mobile](https://github.com/GrinPlusPlus/GrinPlusPlusMobile) - Android. Full node and wallet in your pocket.
- [Ironbelly](https://ironbelly.app) - An iOS/Android wallet for Grin. Open sourced at [cyclefortytwo/ironbelly](https://github.com/cyclefortytwo/ironbelly).

## Explorers

- Grin Explorer [GitHub](https://github.com/mimblewimble/grin-explorer)
  - [GrinExplorer.net](https://grinexplorer.net/) by [@hendi](https://twitter.com/hendi) ([_floonet_](https://floonet.grinexplorer.net/))
  - [Grinmint.com/explorer](https://grinmint.com/explorer/) by [BlockCypher](https://www.blockcypher.com/)
- [GrinScan](https://grinscan.net) maintained by @jaspervdm ([_floonet_](https://floonet.grinscan.net/))
- [Blockscan](https://grin.blockscan.com/) by the same team behind *Etherscan*

## Mining Softwares

- [bminer](https://www.bminer.me/) (Windows & Linux)
- [gminer](https://github.com/develsoftware/GMinerRelease/releases) (Windows & Linux)
- [grin-miner](https://github.com/mimblewimble/grin-miner) reference miner (Linux only)

## Mining Pools

For a comparison of all the different pool hashrates, see [miningpoolstats.stream](https://miningpoolstats.stream/grin-c32).

- [2miners](https://2miners.com/)
- [F2Pool](https://www.f2pool.com)
- [Grinmint](https://www.grinmint.com) by [BlockCypher](https://www.blockcypher.com/) ([Mining guide here](https://blog.blockcypher.com/mining-grin-on-grinmint-a-step-by-step-tutorial-98235c038876))
- [Sparkpool](https://sparkpool.com)

## Payment Processors

- [Knockturn Allee](https://github.com/cyclefortytwo/knockturn-allee) - Open source, self-hosted Grin payment processor.

## Faucet

- [faucet.testnet.grin.lesceller.com](http://faucet.testnet.grin.lesceller.com) - Testnet Faucet
Example usage:
```
curl -d '{"address": "SLATEPACKADDRESS"}' http://faucet.testnet.grin.lesceller.com
```

## Libraries

- [libgrin](https://github.com/blockcypher/libgrin) - A Golang Grin Library
- [grin.py](https://github.com/grinfans/grin.py) - Wallet owner API in Python.
- [Postman Node APIs Collections](https://documenter.getpostman.com/view/12131330/TVsrE8kd) - a postman collection for the Node APIs.

## Other Services

- [Grinbox](https://grinbox.io) - A transaction building service for Grin (for "offline" txs).
