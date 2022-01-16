[![Awesome](https://raw.githubusercontent.com/sindresorhus/awesome/main/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![Bot](https://github.com/naszam/awesome-smart-contracts/actions/workflows/bot.yml/badge.svg)](https://github.com/naszam/awesome-smart-contracts/actions/workflows/bot.yml)

<div align="center">
  <h1 align="center">Awesome Smart Contract Development</h1>
  <p align="center">
    <a href="https://github.com/sindresorhus/awesome">
      <img alt="awesome list badge" src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg">
    </a>
    <a href="#botstatus">
      <img alt="bot status badge" src="https://github.com/naszam/awesome-smart-contracts/actions/workflows/bot.yml/badge.svg">
    </a>
  </p>

  <p align="center">A curated list of awesome <a href="https://ethereum.org/">Ethereum</a> Smart Contract Development resources, tools, security and more.</p>

</div>

# Awesome Smart Contract Development

> A curated list of awesome resources for ethereum smart contract developement

## Contents

  - [Community](#community)
  - [Tools](#tools)
  - [Docs](#docs)
  - [Templates](#templates)
  - [Tutorials](#tutorials)
  - [Certifications](#certifications)
  - [Projects](#projects)
  - [Papers](#papers)
  - [License](#license)

## Community

### Chat
- [Consensys](https://discord.gg/nkK6qbp4Z9)
- [Maker Chat](https://chat.makerdao.com)
- [DappHub Chat](https://dapphub.chat)
- [Empire Hacking Slack ](https://empireslacking.herokuapp.com/)
- [Secureum](discord.gg/ym8BtcWUY2)
- [CryptoDevs](https://discord.gg/xH89RthUUf)
- [Gitter](https://gitter.im/ethereum/solidity/)

### Forum
- [Solidity Forum](https://forum.soliditylang.org/)
- [Ethereum Magicians Forum](https://ethereum-magicians.org/)
- [Maker Forum](https://forum.makerdao.com/)
- [OpenZeppelin Forum](https://forum.openzeppelin.com/)
- [Smart Contract Research Forum](https://www.smartcontractresearch.org/)
- [Ethereum StackExchange](https://ethereum.stackexchange.com/)
- [StarkNet](https://community.starknet.io/)

### Blogs
- [Solidity](https://solidity.ethereum.org/)
- [Vitalik](https://vitalik.ca/)
- [Samczsun](https://samczsun.com/)
- [IPFS](https://blog.ipfs.io/)
- [ConsenSys](https://consensys.net/blog/)

### News
- [Week in Ethereum](https://weekinethereum.substack.com/)
- [EthHub](https://ethhub.substack.com/)
- [Secureum](https://secureum.substack.com)
- [IPFS Weekly](https://ipfs.us4.list-manage.com/subscribe?u=25473244c7d18b897f5a1ff6b&id=cad54b2230)

### Podcasts
- [ZK Podcast](https://zeroknowledge.fm/)
- [Bankless Podcast](http://podcast.banklesshq.com/)
- [The Defiant Podcast](https://thedefiant.io/podcast/)

### Talks

- [DappHub](https://www.youtube.com/watch?v=rKQCvUp5q1w)

### Lists
- [Awesome Solidity](https://github.com/bkrem/awesome-solidity)
    > A curated list of awesome Solidity resources, libraries, tools and more.
- [Ethereum Developer Resources](https://ethereum.org/en/developers/)
    > Guides, resources, and tools for developers building on Ethereum.
- [Awesome DappTools](https://github.com/rajivpo/awesome-dapptools)
    > DappTools Resources
- [Awesome Security Ethereum](https://github.com/crytic/awesome-ethereum-security)
    > A curated list of awesome Ethereum security references, guidance, tools, and more.
- [ConsenSys Ethereum Developer Tools List](https://github.com/ConsenSys/ethereum-developer-tools-list)
    > A guide to available tools, components, patterns, and platforms for developing applications on Ethereum.
- [Awesome IPFS](https://github.com/ipfs/awesome-ipfs)
    > Useful resources for using IPFS and building things on top of it
- [Awesome StarkNet](https://github.com/gakonst/awesome-starknet)

## Tools

### Development
- [DappTools](https://dapp.tools/)
- [Foundry](https://github.com/gakonst/foundry)
- [HardHat](https://github.com/nomiclabs/hardhat)
- [Truffle](https://www.trufflesuite.com/truffle)

### Libraries
- [Solmate](https://github.com/Rari-Capital/solmate)
- [OpenZeppelin Contracts](https://openzeppelin.com/contracts/)

### Unit Testing
- [Hevm](https://github.com/dapphub/dapptools/tree/master/src/hevm)
- [DSTest](https://github.com/dapphub/ds-test)
- [HardHat Network](https://hardhat.org/hardhat-network/)
- [Ganache](https://github.com/trufflesuite/ganache)

### Fuzz Testing
- [Echidna](https://github.com/crytic/echidna)
- [DappTools]()

### Static Analyzers
- [Slither](https://github.com/crytic/slither)
- [Securify v2.0](https://github.com/eth-sri/securify2)
- [MythX CLI](https://docs.mythx.io/tools-integrations/mythx-cli)
- [Remix](https://remix.ethereum.org/)

### Formal Verification
- [KLab](https://github.com/makerdao/klab)
- [Manticore](https://github.com/trailofbits/manticore)
- [Act](https://github.com/ethereum/act)

### Remote Nodes
- [Alchemy](https://www.alchemy.com/)
- [Infura](https://infura.io/)
- [ArchiveNode.io](https://archivenode.io/)
- [QuickNode](https://www.quicknode.com/)
- [Rivet](https://rivet.cloud/)

### Env
- [Maker Nix Packages](https://github.com/makerdao/makerpkgs)
- [Docker-DappTools](https://github.com/OdysLam/ddapptools)

### CI/CD
- [DappTools Maker CI](https://github.com/makerdao/dss/blob/master/.github/workflows/tests.yaml)
- [DappTools Template CI](https://github.com/gakonst/dapptools-template/blob/master/.github/workflows/ci.yml)
- [Forge Template CI](https://github.com/FrankieIsLost/forge-template/blob/master/.github/workflows/CI.yml)
- [HardHat Tests CI](https://github.com/naszam/maker-badges/blob/master/.github/workflows/tests.yml)
- [HardHat Lint CI](https://github.com/naszam/maker-badges/blob/master/.github/workflows/lint.yml)
- [Slither Check CI](https://github.com/naszam/maker-badges/blob/master/.github/workflows/check.yml)
- [Echidna Fuzz CI](https://github.com/naszam/maker-badges/blob/master/.github/workflows/fuzz.yml)
- [Echidna Action](https://github.com/crytic/echidna-action)

### Templates
- [DappTools Template](https://github.com/gakonst/dapptools-template)
- [Forge Template](https://github.com/FrankieIsLost/forge-template)
- [HardHat Template](https://github.com/paulrberg/solidity-template)
- [Merkle Airdrop Starter](https://github.com/Anish-Agnihotri/merkle-airdrop-starter)

### Storage
- [IPFS](https://ipfs.io/)
- [Pinata](https://www.pinata.cloud/)
- [Arweave](https://www.arweave.org/)

### Utilities
- [duppgrade](https://github.com/Rari-Capital/duppgrade)
- [duppsolc](https://github.com/naszam/duppsolc)
- [forgeup](https://github.com/transmissions11/forgeup)
- [seth helpers](https://gist.github.com/mds1/3f070676129a095dec372c2d02cedfdd)
- [HEVM Helpers](https://github.com/brockelmore/HEVMHelpers)
- [ethereumjs-util](https://github.com/ethereumjs/ethereumjs-util)
- [Etherscan](https://etherscan.io/)
- [Tenderly](https://tenderly.co/)

### Front-End
- [Uniswap Interface](https://github.com/Uniswap/interface)
- [Dai.js Boilerplate](https://github.com/makerdao/nextjs-daijs-dai-ui-example)
- [Ethers.js](https://github.com/ethers-io/ethers.js/)
- [Ethers Playground](https://playground.ethers.org/)
- [Ethers.rs](https://github.com/gakonst/ethers-rs)
- [Web3.js](https://github.com/ethereum/web3.js)
- [Fleek](https://fleek.co/)
- [Playroom](https://github.com/seek-oss/playroom)


## Docs
- [Solidity](https://solidity.readthedocs.io/en/latest/)
- [DappTools](https://github.com/dapphub/dapptools#dapp-tools-by-dapphub-)
- [Dapp](https://github.com/dapphub/dapptools/tree/master/src/dapp#dapp-)
- [Seth](https://github.com/dapphub/dapptools/tree/master/src/seth#seth)
- [Hevm](https://github.com/dapphub/dapptools/tree/master/src/hevm#hevm-)
- [Ethsign](https://github.com/dapphub/dapptools/tree/master/src/ethsign#ethsign)
- [Forge](https://github.com/gakonst/foundry/tree/master/forge)
- [Cast](https://github.com/gakonst/foundry/tree/master/cast)
- [HardHat](https://hardhat.org/getting-started/)
- [OpenZeppelin](https://docs.openzeppelin.com/openzeppelin/)
- [Truffle](https://www.trufflesuite.com/docs/truffle/overview)
- [Ganache](https://www.trufflesuite.com/docs/ganache/overview)
- [Ethers.js](https://docs.ethers.io/)
- [Web3.js](https://web3js.readthedocs.io/)
- [Ethers.rs](https://docs.rs/ethers/latest/ethers/)

## Tutorials

### DappTools
- [DappTools Basic Usage](https://github.com/dapphub/dapptools/tree/master/src/dapp#basic-usage-a-tutorial)
- [Introduction to Seth](https://docs.makerdao.com/clis/seth)
- [Symbolic Execution With ds-test](https://fv.ethereum.org/2020/12/11/symbolic-execution-with-ds-test/)
- [HEVM and Seth Cheatsheet](https://kndrck.co/posts/hevm_seth_cheatsheet/)
- [Use dapp.tools for Ethereum Contract Development](https://medium.com/coinmonks/use-dapp-tools-for-ethereum-contract-development-2775d8b2ba0)
- [Programming a simple ERC20 token - Part 1](https://www.youtube.com/watch?v=Hqx5yuskmRU&list=PLYSZ-f9LCH3sEf0UKTLCaZErJeQtK7GCD) :movie_camera:
- [Programming a simple ERC20 token - Part 2](https://www.youtube.com/watch?v=ifHdJQM6AlE) :movie_camera:
- [Programming a simple ERC20 token - Part 3](https://www.youtube.com/watch?v=ejkaRMcW2JM) :movie_camera:
- [Programming a simple ERC20 token - Part 4](https://www.youtube.com/watch?v=PRXZ499LqNk) :movie_camera:
- [Programming a simple ERC20 token - Part 5](https://www.youtube.com/watch?v=qs4Q-BMb9ms) :movie_camera:
- [Become a Dapptools Pilled Chad in 30 minutes or Your Money Back](https://youtu.be/N9pJ9JieX10)
- [Smart Contract Development with dapp.tools](https://youtu.be/lPinWgaNceM)

### Forge
- [Getting Started With Forge](https://w.mirror.xyz/mOUlpgkWA178HNUW7xR20TdbGRV6dMid7uChqxf9Z58)

## Certifications
- [Blockchain Developer Bootcamp ConsenSys Academy](https://consensys.net/academy/bootcamp/)

## Projects

### DappTools
- [Multi Collateral Dai](https://github.com/makerdao/dss)
- [DSS ChainLog](https://github.com/makerdao/dss-chain-log)
- [DSS Deploy](https://github.com/makerdao/dss-deploy)
- [DSS Deploy Scripts](https://github.com/makerdao/dss-deploy-scripts)
- [DSS Spells](https://github.com/makerdao/spells-mainnet)
- [DSS Exec Lib](https://github.com/makerdao/dss-exec-lib)
- [DSS Ilk Registry](https://github.com/makerdao/ilk-registry)
- [DSS Proxy Actions](https://github.com/makerdao/dss-proxy-actions)
- [DSS CDP Manager](https://github.com/makerdao/dss-cdp-manager)
- [DSS MegaPoker](https://github.com/makerdao/megapoker)
- [DSS PSM](https://github.com/makerdao/dss-psm)
- [DSS Vest](https://github.com/makerdao/dss-vest)
- [DSS Charter](https://github.com/makerdao/dss-charter)
- [DS Token](https://github.com/dapphub/ds-token)
- [DS Deed](https://github.com/brianmcmichael/ds-deed)
- [Chai](https://github.com/dapphub/chai)
- [Multicall](https://github.com/makerdao/multicall)
- [MCD Setzer](https://github.com/makerdao/setzer-mcd)
- [Single Collateral Dai](https://github.com/makerdao/sai)
- [Dappsys](https://github.com/dapphub/dappsys)
- [Dappsys V2](https://github.com/dapp-org/dappsys-v2)
- [ETH2 Deposit Contract](https://github.com/ethereum/consensus-specs/tree/dev/solidity_deposit_contract)
- [Maple Finance](https://github.com/maple-labs/maple-core)
- [Fractional](https://github.com/fractional-company/contracts)
- [K DSS](https://github.com/dapphub/k-dss)

### HardHat
- [Optimism Dai Bridge](https://github.com/makerdao/optimism-dai-bridge)
- [Arbitrum Dai Bridge](https://github.com/makerdao/arbitrum-dai-bridge)
- [Uniswap V3](https://github.com/Uniswap/v3-core)
- [GUNI v1 Core](https://github.com/gelatodigital/g-uni-v1-core)

## Papers
- [Ethereum: A Next Generation Smart Contract and Decentralized Application Platform](https://ethereum.org/whitepaper/)
- [Ethereum: A Secure Decentralised Generalised Transaction Ledger](https://ethereum.github.io/yellowpaper/paper.pdf)
- [Smart Contracts by Nick Szabo](https://drive.google.com/file/d/1fQpwlpWToDyBMyBhZDobS29Szn4xpXeH/view)  
- [Smart Contracts: Building Blocks for Digital Markets](https://www.fon.hum.uva.nl/rob/Courses/InformationInSpeech/CDROM/Literature/LOTwinterschool2006/szabo.best.vwh.net/smart_contracts_2.html)

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
