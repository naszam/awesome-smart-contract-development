[![Awesome](https://raw.githubusercontent.com/sindresorhus/awesome/main/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![Bot](https://github.com/naszam/awesome-smart-contracts/actions/workflows/bot.yml/badge.svg)](https://github.com/naszam/awesome-smart-contracts/actions/workflows/bot.yml)

# Awesome Smart Contracts

> A curated list of awesome resources for ethereum smart contract developers

## Contents

  - [Community](#community)
  - [Tools](#tools)
  - [Docs](#docs)
  - [Templates](#templates)
  - [Tutorials](#tutorials)
  - [Security](#security)
  - [Certifications](#certifications)
  - [Projects](#projects)
  - [Smart Contracts Development](#smart-contract-development)
    - [Blockchain 101](#blockchain-101)
    - [Ethereum 101](#ethereum-101)
    - [DApp Development](#dapp-development)
    - [Development Frameworks and Environment](#development-frameworks-and-environment)
    - [Solidity 101](#solidity-101)
    - [Solidity 201](#solidity-201)
    - [References](#references)
  - [License](#license)

## Community

### Chat
- [Consensys](https://discord.gg/sEyGNY) - #developers
- [Maker Chat](https://chat.makerdao.com) - #dev
- [DappHub Chat](https://dapphub.chat) - #dev
- [Empire Hacking Slack ](https://empireslacking.herokuapp.com/) - #ethereum
- [CryptoDevs](https://discord.gg/NC9D7x) - :memo:-solidity-dev
- [Gitter](https://gitter.im/ethereum/solidity/) - ethereum/solidity

### Forum
- [Solidity Forum](https://forum.soliditylang.org/)
- [Ethereum Magicians Forum](https://ethereum-magicians.org/)
- [Maker Forum](https://forum.makerdao.com/)
- [OpenZeppelin Forum](https://forum.openzeppelin.com/)
- [Smart Contract Research Forum](https://www.smartcontractresearch.org/)
- [Ethereum StackExchange](https://ethereum.stackexchange.com/)

### Blogs
- [Solidity](https://solidity.ethereum.org/)
- [Vitalik](https://vitalik.ca/)
- [Samczsun](https://samczsun.com/)
- [IPFS](https://blog.ipfs.io/)
- [ConsenSys](https://consensys.net/blog/)

### News
- [Week in Ethereum](https://weekinethereum.substack.com/)
- [EthHub](https://ethhub.substack.com/)
- [IPFS Weekly](https://ipfs.us4.list-manage.com/subscribe?u=25473244c7d18b897f5a1ff6b&id=cad54b2230)

### Podcasts
- [ZK Podcast](https://zeroknowledge.fm/)
- [Bankless Podcast](http://podcast.banklesshq.com/)
- [The Defiant Podcast](https://thedefiant.io/podcast/)

### Talks

- [DappHub](https://www.youtube.com/watch?v=rKQCvUp5q1w)
- [Smart Contract Development with dapp.tools](https://www.youtube.com/watch?v=lPinWgaNceM)

### Lists
- [Awesome DappTools](https://github.com/rajivpo/awesome-dapptools)
    > DappTools Resources
- [Awesome IPFS](https://github.com/ipfs/awesome-ipfs)
    > Useful resources for using IPFS and building things on top of it
- [Awesome Security Ethereum](https://github.com/crytic/awesome-ethereum-security)
    > A curated list of awesome Ethereum security references, guidance, tools, and more.
- [Awesome Solidity](https://github.com/bkrem/awesome-solidity)
    > A curated list of awesome Solidity resources, libraries, tools and more.
- [Ethereum Developer Resources](https://ethereum.org/en/developers/)
    > Guides, resources, and tools for developers building on Ethereum.
- [ConsenSys Ethereum Developer Tools List](https://github.com/ConsenSys/ethereum-developer-tools-list)
    > A guide to available tools, components, patterns, and platforms for developing applications on Ethereum.

## Tools

### Smart Contracts
- [DappTools](https://dapp.tools/)
- [Truffle](https://www.trufflesuite.com/truffle)
- [OpenZeppelin Contracts](https://openzeppelin.com/contracts/)
- [OpenGSN](https://github.com/opengsn/gsn)
- [IPFS](https://github.com/ipfs/ipfs)
- [AZTEC Protocol](https://github.com/AztecProtocol/AZTEC)
- [Infura](https://infura.io/)
- [Truffle HD Wallet Provider](https://www.npmjs.com/package/@truffle/hdwallet-provider)
- [Truffle Flattener](https://github.com/nomiclabs/truffle-flattener)

### Tests
- [Hevm](https://github.com/dapphub/dapptools/tree/master/src/hevm)
- [Ganache](https://www.trufflesuite.com/ganache)
- [OpenZeppelin Test Environment](https://github.com/OpenZeppelin/openzeppelin-test-environment)
- [Jest](https://jestjs.io/)
- [Truffle Teams](https://www.trufflesuite.com/teams)

### Front-End
- [Drizzle](https://www.trufflesuite.com/drizzle)
- [Uniswap Frontend](https://github.com/Uniswap/uniswap-frontend)
- [Dai.js Boilerplate](https://github.com/makerdao/nextjs-daijs-dai-ui-example)
- [Next.js](https://github.com/vercel/next.js)
- [Truffle React Box](https://www.trufflesuite.com/boxes/react)
- [Ethers.js](https://github.com/ethers-io/ethers.js/)
- [Web3.js](https://github.com/ethereum/web3.js)
- [Fleek](https://fleek.co/)

### Utilities
- [duppgrade](https://github.com/Rari-Capital/duppgrade)
- [seth helpers](https://gist.github.com/mds1/3f070676129a095dec372c2d02cedfdd)
- [HEVM Helpers](https://github.com/brockelmore/HEVMHelpers)
- [ethereumjs-util](https://github.com/ethereumjs/ethereumjs-util)
- [Etherscan](https://etherscan.io/)
- [Tenderly](https://tenderly.co/)
- [Playroom](https://github.com/seek-oss/playroom)

### Env
- [Maker Nix Packages](https://github.com/makerdao/makerpkgs)
- [Docker-DappTools](https://github.com/OdysLam/ddapptools)

### CI/CD
- [DappTools Maker CI](https://github.com/makerdao/dss/blob/master/.github/workflows/tests.yaml)
- [DappTools Template CI](https://github.com/gakonst/dapptools-template/blob/master/.github/workflows/ci.yml)

## Docs
- [DappTools](https://github.com/dapphub/dapptools#dapp-tools-by-dapphub-)
- [Dapp](https://github.com/dapphub/dapptools/tree/master/src/dapp#dapp-)
- [Seth](https://github.com/dapphub/dapptools/tree/master/src/seth#seth)
- [Hevm](https://github.com/dapphub/dapptools/tree/master/src/hevm#hevm-)
- [Ethsign](https://github.com/dapphub/dapptools/tree/master/src/ethsign#ethsign)
- [Solidity](https://solidity.readthedocs.io/en/latest/)
- [OpenZeppelin](https://docs.openzeppelin.com/openzeppelin/)
- [OpenGSN](https://docs.opengsn.org/contracts/index.html)
- [Truffle](https://www.trufflesuite.com/docs/truffle/overview)
- [Ganache](https://www.trufflesuite.com/docs/ganache/overview)
- [Drizzle](https://www.trufflesuite.com/docs/drizzle/overview)
- [Truffle Teams](https://www.trufflesuite.com/docs/teams/overview)
- [Web3.js](https://web3js.readthedocs.io/)
- [Ethers.js](https://docs.ethers.io/)
- [Jest.js](https://jestjs.io/docs/en/using-matchers)

## Templates

- [DappTools Template](https://github.com/gakonst/dapptools-template)
- [HardHat Template](https://github.com/paulrberg/solidity-template)

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

### Testing
- [OpenZeppelin Test Environment](https://docs.openzeppelin.com/test-environment/0.1/getting-started)
- [Testing on Mainnet with Jest, Ganache, and Uniswap](https://studydefi.com/testing-on-mainnet/)
- [Buidler's tutorial for beginners](https://buidler.dev/tutorial/)

## Security

### Static Analyzers
- [Slither](https://github.com/crytic/slither)
- [Securify v2.0](https://github.com/eth-sri/securify2)
- [MythX CLI](https://docs.mythx.io/tools-integrations/mythx-cli)
- [Remix](https://remix.ethereum.org/)

### Fuzzer
- [Echidna](https://github.com/crytic/echidna)

### Formal Verification
- [KLab](https://github.com/makerdao/klab)
- [Manticore](https://github.com/trailofbits/manticore)
- [Act](https://github.com/ethereum/act)

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

## Smart Contract Development

### Blockchain 101

#### Consensus Algorithms
- [Byzantine Generals Problem](https://en.wikipedia.org/wiki/Byzantine_fault#Byzantine_Generals'_Problem)
- [Types of Consensus](https://mastanbtc.github.io/blockchainnotes/consensustypes/)
- [Podcast: Overview and History of Consensus System Development](https://softwareengineeringdaily.com/2018/03/26/consensus-systems-with-ethan-buchman/)
- [Understanding Distributed Consensus](https://medium.com/s/story/lets-take-a-crack-at-understanding-distributed-consensus-dad23d0dc95)

#### Mining
- [Ethereum Wiki on Mining](https://eth.wiki/en/fundamentals/mining)

#### Cryptographic Hash Functions
- [Blockchain Underpinnings: Hashing by ConsenSys Media](https://medium.com/@ConsenSys/blockchain-underpinnings-hashing-7f4746cbd66b)
- [Cryptographic hash functions on Wikipedia](https://simple.wikipedia.org/wiki/Cryptographic_hash_function)
- [Cryptographic hash functions by the Kahn Academy](https://www.khanacademy.org/economics-finance-domain/core-finance/money-and-banking/bitcoin/v/bitcoin-cryptographic-hash-function)
- [Video: Hashing Algorithms and Security by Computerphile](https://www.youtube.com/watch?v=b4b8ktEV4Bg)

#### Public Key Cryptography
- [Wikipedia: Public Key Cryptography](https://en.wikipedia.org/wiki/Public-key_cryptography)

#### Merkle Trees
- [Merkling in Ethereum by Vitalik Buterin](https://blog.ethereum.org/2015/11/15/merkling-in-ethereum/)
- [Ever Wonder How Merkle Trees Work? by ConsenSys Media](https://media.consensys.net/ever-wonder-how-merkle-trees-work-c2f8b7100ed3)
- [Patricia Merkle Trees](https://eth.wiki/en/fundamentals/patricia-tree)

#### Blockchain Structure
- [A visual demonstration of a blockchain data structure](https://andersbrownworth.com/blockchain/)
- [Bitcoin Wiki - Blockchain](https://en.bitcoin.it/wiki/Block_chain)
- [Blockchain Basics](https://solidity.readthedocs.io/en/develop/introduction-to-smart-contracts.html#blockchain-basics)

#### Smart Contracts
- [Introduction to Smart Contracts](https://solidity.readthedocs.io/en/develop/introduction-to-smart-contracts.html#)

#### Nodes

#### Blockchain Forks
- [Hard Forks, Soft Forks, Defaults and Coercion by Vitalik Buterin](https://vitalik.ca/general/2017/03/14/forks_and_markets.html)

### Ethereum 101

#### Accounts
- [Hexadecimal format](https://en.wikipedia.org/wiki/Hexadecimal)
- [How are Ethereum Addresses Generated?](https://ethereum.stackexchange.com/questions/3542/how-are-ethereum-addresses-generated)
- [Solidity Docs on Accounts](https://solidity.readthedocs.io/en/v0.4.20/introduction-to-smart-contracts.html#accounts)
- [An externally owned account on Etherscan](https://etherscan.io/address/0x1b3947bd020227455563a5df59a06a42bd63f409)
- [A contract account on Etherscan](https://etherscan.io/address/0xde0b295669a9fd93d5f28d9ec85e40f4cb697bae)
- [How is the address of an Ethereum contract computed?](https://ethereum.stackexchange.com/questions/760/how-is-the-address-of-an-ethereum-contract-computed)
- [More about CREATE2](https://ethgasstation.info/blog/what-is-create2/)

#### Transactions
- [How does Ethereum verify contract execution?](https://www.quora.com/How-does-Ethereum-verify-contract-execution)
- [Solidity Docs on Transactions](https://solidity.readthedocs.io/en/latest/introduction-to-smart-contracts.html#transactions)
- [What is the difference between a transaction and a contract message?](https://ethereum.stackexchange.com/questions/12065/what-is-the-difference-between-a-call-message-call-and-a-message)

#### Gas and Fees
- [Ethereum, Gas, Fuel and Fees - Consensys Media](https://media.consensys.net/ethereum-gas-fuel-and-fees-3333e17fe1dc)
- [EthGasStation](https://ethgasstation.info/)

#### Ethereum Structure
- [How does Ethereum work anyway?](https://medium.com/@preethikasireddy/how-does-ethereum-work-anyway-22d1df506369)
- [Ethereum Block Architecture](https://ethereum.stackexchange.com/questions/268/ethereum-block-architecture)
- [Ethereum Development tutorial](https://github.com/ethereum/wiki/wiki/Ethereum-Development-Tutorial)
- [Ethstats](https://ethstats.net/)

#### Ethereum Addresses
- [Ethereum yellow paper](http://gavwood.com/paper.pdf)

### Dapp Development

#### Decentralized Application Development
- [Ethereum for Web Developers](https://medium.com/@mvmurthy/ethereum-for-web-developers-890be23d1d0c)
- [A Brief Overview of dapp Development](https://thecontrol.co/a-brief-overview-of-dapp-development-b8ac1648322c?gi=9ece1030a15c)
- [Building for Blockchain: Transitioning from Web 2.0 to Web 3.0 ](https://blog.ycombinator.com/building-for-the-blockchain/)

#### Development Environment Setup Options
- [The Go-Ethereum (Geth) Github Repo](https://github.com/ethereum/go-ethereum/wiki/geth)
- [Infura: A public API Interface for Ethereum](https://infura.io/product/overview)

#### Key Developer Tools
- [Metamask: Chrome Extension for Ethereum](https://metamask.io/download.html)
- [Remix: an in-browser IDE for Smart Contract Development](https://remix.ethereum.org/#optimize=false&evmVersion=null)
- [Truffle: A Blockchain Development Framework](https://www.trufflesuite.com/)
- [Truffle Ganache: A Private Testnet for Blockchain Development](https://github.com/trufflesuite/ganache)
- [Web3.js: Javascript Library for Ethereum + front-end integration](https://web3js.readthedocs.io/en/v1.2.9/)
- [IPFS website: Distributed File Storage Mechanism](https://ipfs.io/)
- [Swarm documentation: Distributed File Storage within Geth](https://swarm-guide.readthedocs.io/en/latest/introduction.html)

#### Geth
- [Getting started with Geth](https://geth.ethereum.org/docs/getting-started)
- [Setup Your Own Private Proof of Authority Ethereum Network with Geth](https://hackernoon.com/setup-your-own-private-proof-of-authority-ethereum-network-with-geth-9a0a3750cda8)
- ["Proof of Authority Chains," Parity Technologies](https://openethereum.github.io/Proof-of-Authority-Chains.html)
- ["Proof-of-Authority Tutorial," Parity Technologies](https://openethereum.github.io/Demo-PoA-tutorial.html)
- ["Using Puppeth to Manually Create an Ethereum Proof-of-Authority Clique Network using AWS," Collin Cusce](https://medium.com/@collin.cusce/using-puppeth-to-manually-create-an-ethereum-proof-of-authority-clique-network-on-aws-ae0d7c906cce)
- [Clique PoA Protocol Details, Péter Szilágyi & Ethereum Foundation](https://github.com/ethereum/EIPs/issues/225)
- [Cliquebait Repo, from FOAM](https://github.com/f-o-a-m/cliquebait)

### Development Frameworks and Environment

#### MetaMask
- [Metamask.io](https://metamask.io/)
- [Metamask Developer Documentation](https://docs.metamask.io/guide/)

#### Ganache CLI
- [Ganache-cli on npm](https://www.npmjs.com/package/ganache-cli)

#### Ganache GUI
- [Download Ganache GUI](https://github.com/trufflesuite/ganache-ui/releases)

### Solidity 101

#### Data Types and Variables
- [Solidity Docs - Types](https://solidity.readthedocs.io/en/develop/types.html)
- [Solidity Docs - Contract Types](https://solidity.readthedocs.io/en/develop/types.html#contract-types)
 
#### Functions
- [Solidity docs - Functions](https://solidity.readthedocs.io/en/develop/contracts.html#functions)
- [Solidity docs - Function Types](https://solidity.readthedocs.io/en/develop/types.html?highlight=function%20types#function-types)

#### Storage and Memory
- [Difference between memory and storage](https://ethereum.stackexchange.com/questions/1232/difference-between-memory-and-storage)
- [Storage, Memory and the Stack](https://solidity.readthedocs.io/en/develop/introduction-to-smart-contracts.html#storage-memory-and-the-stack)
- [Data location -- Solidity Docs](https://solidity.readthedocs.io/en/develop/types.html#data-location)

#### Contract Structure
- [Structure of a Contract](https://solidity.readthedocs.io/en/develop/structure-of-a-contract.html)
- [Smart contracts as a State Machine](https://solidity.readthedocs.io/en/develop/common-patterns.html?#state-machine)
- [Solidity Inline Assembly](https://solidity.readthedocs.io/en/develop/assembly.html)

#### Reading Smart Contracts with Remix
- [Remix Workshops](https://github.com/ethereum/remix-workshops)
- [Solidity by Example - Solidity Docs](https://solidity.readthedocs.io/en/develop/solidity-by-example.html)

#### Smart Contract ABI
- [Solidity Docs - ABI](https://solidity.readthedocs.io/en/latest/abi-spec.html)
- [What is the ABI and why is it needed to interact with contracts](https://ethereum.stackexchange.com/questions/234/what-is-an-abi-and-why-is-it-needed-to-interact-with-contracts)

#### Events and Logs
- [Events - Solidity Docs](https://solidity.readthedocs.io/en/develop/contracts.html#events)
- [Listening to events with web3.js](https://web3js.readthedocs.io/en/v1.5.2/web3-eth-subscribe.html?highlight=events#subscribe-logs)
- [Listening to events via the contract object](https://web3js.readthedocs.io/en/v1.5.2/web3-eth-contract.html#contract-events)

#### Factory Contracts

### Solidity 201

#### Introductory Smart Contracts

#### Inter-Contract Execution
- [Difference between call, callcode and delegatecall - stackexchange](https://ethereum.stackexchange.com/questions/3667/difference-between-call-callcode-and-delegatecall)

#### Inheritance
- [Inheritance, from the Solidity Docs](https://solidity.readthedocs.io/en/develop/contracts.html#inheritance)
- [Abstract contracts](https://solidity.readthedocs.io/en/latest/contracts.html#abstract-contracts)
- [Interfaces](https://solidity.readthedocs.io/en/latest/contracts.html#interfaces)

#### Libraries
- [Libraries in the Solidity Docs](https://solidity.readthedocs.io/en/develop/contracts.html#libraries)

### References
- [Smart Contracts by Nick Szabo](https://drive.google.com/file/d/1fQpwlpWToDyBMyBhZDobS29Szn4xpXeH/view)  
- [Smart Contracts: Building Blocks for Digital Markets](https://www.fon.hum.uva.nl/rob/Courses/InformationInSpeech/CDROM/Literature/LOTwinterschool2006/szabo.best.vwh.net/smart_contracts_2.html)
- [Ethereum: A Next Generation Smart Contract and Decentralized Application Platform](https://ethereum.org/whitepaper/)
- [Ethereum: A Secure Decentralised Generalised Transaction Ledger](https://ethereum.github.io/yellowpaper/paper.pdf)

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
