# Awesome Smart Contracts [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of awesome resources for ethereum smart contract developers

## Table of Contents

- [Community](#community)
  - [Chat](#chat)
  - [Forum](#forum)
  - [Blogs](#blogs)
  - [News](#news)
  - [Lists](#lists)
- [Tools](#tools)
  - [Smart Contracts](#smart-contracts)
  - [Tests](#tests)
  - [Front-End](#front-end)
  - [Utilities](#utilities)
- [Docs](#docs)
- [Tutorials](#tutorials)
  - [Testing](#testing)
- [Security](#security)
  - [Static Analyzers](#static-analyzers)
  - [Fuzzer](#fuzzer)
  - [Formal Verification](#formal-verification)
- [Certifications](#certifications)
- [Crypto Degree](#crypto-degree)
  - [Blockchain Technology](#blockchain-technology)
    - [Consensus Algorithms](#consensus-algorithms)
    - [Mining](#mining)
    - [Public and Private Blockchains](#public-and-private-blockchains)
    - [Distributed Ledger Platforms](#distributed-ledger-platforms)
   - [Blockchain Primitives](#blockchain-primitives)
      - [Cryptographic Hash Functions](#cryptographic-hash-functions)
      - [Public Key Cryptography](#public-key-cryptography)
      - [Merkle Trees](#merkle-trees)
      - [Blockchain Structure](#blockchain-structure)
      - [Smart Contracts](#smart-contracts)
      - [Nodes](#nodes)
      - [Blockchain Forks](#blockchain-forks)
  - [Ethereum Basics](#ethereum-basics)
    - [Accounts](#accounts)
    - [Transactions](#transactions)
    - [Gas and Fees](#gas-and-fees)
    - [Ethereum Structure](#ethereum-structure)
    - [Ethereum Addresses](#ethereum-addresses)
  - [Traditional and Decentralized Application Development](#traditional-and-decentralized-application-development)
    - [Decentralized Application Development](#decentralized-application-development)
    - [Development Environment Setup Options](#development-environment-setup-options)
    - [Key Developer Tools](#key-developer-tools)
    - [Geth](#geth)
  - [Development Frameworks and Environment](#development-frameworks-and-environment)
    - [MetaMask](#metamaks)
    - [Ganache CLI](#ganache-cli)
    - [Truffle](#truffle)
    - [Ganache GUI](#ganache-gui)
  - [Solidity Fundamentals](#solidity-fundamentals)
    - [Data Types and Variables](#data-types-and-variables)
    - [Functions](#functions)
    - [Storage and Memory](#storage-and-memory)
    - [Contract Structure](#contract-structure)
    - [Reading Smart Contracts with Remix](#reading-smart-contracts-with-remix)
    - [Smart Contract ABI](#smart-contract-abi)
    - [Events and Logs](#events-and-logs)
    - [Factory Contracts](#factory-contracts)
  - [Writing Smart Contracts](#writing-smart-contracts)
    - [Introductory Smart Contracts](#introductory-smart-contracts)
    - [Inter-Contract Execution](#inter-contract-execution)
    - [Inheritance](#inheritance)
    - [Libraries and the Ethereum Package Manager](#libraries-and-the-ethereum-package-manager)
- [References](#references)
- [License](#license)

## Community

### Chat
- [Gitter](https://gitter.im/ethereum/solidity/) - ethereum/solidity 
- [CryptoDevs](https://discord.gg/NC9D7x) - :memo:-solidity-dev 
- [Maker Chat](https://chat.makerdao.com) - #dev
- [DappHub Chat](https://dapphub.chat) - #dev
- [Consensys](https://discord.gg/sEyGNY) - #developers

### Forum
- [OpenZeppelin Forum](https://forum.openzeppelin.com/)
- [Ethereum StackExchange](https://ethereum.stackexchange.com/)
- [Maker Forum](https://forum.makerdao.com/)

### Blogs
- [Solidity](https://solidity.ethereum.org/)
- [Vitalik](https://vitalik.ca/)
- [IPFS](https://blog.ipfs.io/)
- [ConsenSys](https://consensys.net/blog/)
### News
- [Week in Ethereum](https://weekinethereumnews.com/)
- [EthHub](https://ethhub.substack.com/)
- [IPFS Weekly](https://ipfs.us4.list-manage.com/subscribe?u=25473244c7d18b897f5a1ff6b&id=cad54b2230)

### Lists
- [Awesome IPFS](https://github.com/ipfs/awesome-ipfs) - Useful resources for using IPFS and building things on top of it  
- [Awesome Security Ethereum](https://github.com/crytic/awesome-ethereum-security) - A curated list of awesome Ethereum security references, guidance, tools, and more.  
- [Awesome Solidity](https://github.com/bkrem/awesome-solidity) - A curated list of awesome Solidity resources, libraries, tools and more.  
- [Ethereum Developer Resources](https://ethereum.org/en/developers/)

## Tools

### Smart Contracts
- [Truffle](https://www.trufflesuite.com/truffle)
- [OpenZeppelin Contracts](https://openzeppelin.com/contracts/)
- [OpenGSN](https://github.com/opengsn/gsn)
- [IPFS](https://github.com/ipfs/ipfs)
- [AZTEC Protocol](https://github.com/AztecProtocol/AZTEC)
- [Infura](https://infura.io/)
- [Truffle HD Wallet Provider](https://www.npmjs.com/package/@truffle/hdwallet-provider)
- [Truffle Flattener](https://github.com/nomiclabs/truffle-flattener)

### Tests
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
- [ethereumjs-util](https://github.com/ethereumjs/ethereumjs-util)
- [Etherscan](https://etherscan.io/)
- [Tenderly](https://tenderly.co/)
- [Playroom](https://github.com/seek-oss/playroom)

## Docs
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

## Tutorials

### Testing
- [OpenZeppelin Test Environment](https://docs.openzeppelin.com/test-environment/0.1/getting-started)
- [Testing on Mainnet with Jest, Ganache, and Uniswap](https://studydefi.com/testing-on-mainnet/)
- [Buidler's tutorial for beginners](https://buidler.dev/tutorial/)

## Security

### Static Analyzers
- [Slither](https://github.com/crytic/slither)
- [MythX CLI](https://docs.mythx.io/tools-integrations/mythx-cli)
- [Remix](https://remix.ethereum.org/)

### Fuzzer
- [Echidna](https://github.com/crytic/echidna)

### Formal Verification
- [Manticore](https://github.com/trailofbits/manticore)

## Certifications
- [Blockchain Developer Bootcamp ConsenSys Academy](https://consensys.net/academy/bootcamp/)

## Crypto Degree

### Blockchain Technology

#### Consensus Algorithms
- [Byzantine Generals Problem](https://en.wikipedia.org/wiki/Byzantine_fault#Byzantine_Generals'_Problem)
- [Types of Consensus](https://mastanbtc.github.io/blockchainnotes/consensustypes/)
- [Podcast: Overview and History of Consensus System Development](https://softwareengineeringdaily.com/2018/03/26/consensus-systems-with-ethan-buchman/)
- [Understanding Distributed Consensus](https://medium.com/s/story/lets-take-a-crack-at-understanding-distributed-consensus-dad23d0dc95)

#### Mining
- [Live visualization of block formation](http://ethviewer.live/)
- [Ethereum Wiki on Mining](https://eth.wiki/en/fundamentals/mining)

#### Public and Private Blockchains
- [On public and private blockchains by Vitalik Buterin](https://blog.ethereum.org/2015/08/07/on-public-and-private-blockchains/)

#### Distributed Ledger Platforms
- [Enterprise Blockchain Protocols: A Technical Analysis of Ethereum vs Fabric vs Corda](https://www.kaleido.io/blockchain-blog/enterprise-blockchain-protocols-a-technical-analysis-of-ethereum-vs-fabric-vs-corda)

### Blockchain Primitives

#### Cryptographic Hash Functions
- [Blockchain Underpinnings: Hashing by ConsenSys Media](https://medium.com/@ConsenSys/blockchain-underpinnings-hashing-7f4746cbd66b)
- [Cryptographic hash functions on Wikipedia](https://simple.wikipedia.org/wiki/Cryptographic_hash_function)
- [Cryptographic hash functions by the Kahn Academy](https://www.khanacademy.org/economics-finance-domain/core-finance/money-and-banking/bitcoin/v/bitcoin-cryptographic-hash-function)
- [Video: Hashing Algorithms and Security by Computerphile](https://www.youtube.com/watch?v=b4b8ktEV4Bg)

#### Public Key Cryptography
- [How are Ethereum addresses generated?](https://ethereum.stackexchange.com/questions/3542/how-are-ethereum-addresses-generated)
- [Wikipedia: Public Key Cryptography](https://en.wikipedia.org/wiki/Public-key_cryptography)

#### Merkle Trees
- [Merkling in Ethereum by Vitalik Buterin](https://blog.ethereum.org/2015/11/15/merkling-in-ethereum/)
- [Ever Wonder How Merkle Trees Work? by ConsenSys Media](https://media.consensys.net/ever-wonder-how-merkle-trees-work-c2f8b7100ed3)
- [Patricia Merkle Trees](https://eth.wiki/en/fundamentals/patricia-tree)

#### Blockchain Structure
- [A visual demonstration of a blockchain data structure](https://andersbrownworth.com/blockchain/)
- [Bitcoin Wiki - Blockchain](https://en.bitcoin.it/wiki/Block_chain)
- [https://solidity.readthedocs.io/en/develop/introduction-to-smart-contracts.html#blockchain-basics](https://solidity.readthedocs.io/en/develop/introduction-to-smart-contracts.html#blockchain-basics)

#### Smart Contracts
- [Introduction to Smart Contracts](https://solidity.readthedocs.io/en/develop/introduction-to-smart-contracts.html#)
- [What is a smart contract?](https://coinsutra.com/smart-contracts/)

#### Nodes
- [What is an Ethereum node?](https://www.reddit.com/r/ethereum/comments/4dx6km/newbie_question_what_is_ethereum_node/)

#### Blockchain Forks
- [Hard Forks, Soft Forks, Defaults and Coercion by Vitalik Buterin](https://vitalik.ca/general/2017/03/14/forks_and_markets.html)
- [Short guide to bitcoin forks - Coindesk](https://www.coindesk.com/short-guide-bitcoin-forks-explained)
- [Map of coins: Visualized history of Bitcoin forks and altcoins](https://mapofcoins.com/bitcoin)

### Ethereum Basics

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
- [Understanding the concept of private keys, public keys and addresses in Ethereum](https://etherworld.co/2017/11/17/understanding-the-concept-of-private-key-public-key-and-address-in-ethereum-blockchain/)
- [Bitcoin wiki on Secp256k1](https://en.bitcoin.it/wiki/Secp256k1)
- [Ethereum yellow paper](http://gavwood.com/paper.pdf)

### Traditional and Decentralized Application Development

#### Decentralized Application Development
- [Why use a blockchain?](https://www.coindesk.com/learn/blockchain-101/how-blockchain-technology-change-finance)
- [Ethereum for Web Developers](https://medium.com/@mvmurthy/ethereum-for-web-developers-890be23d1d0c)
- [A Brief Overview of dapp Development](https://thecontrol.co/a-brief-overview-of-dapp-development-b8ac1648322c?gi=9ece1030a15c)
- [Building for Blockchain: Transitioning from Web 2.0 to Web 3.0 ](https://blog.ycombinator.com/building-for-the-blockchain/)

#### Development Environment Setup Options
- [The Go-Ethereum (Geth) Github Repo](https://github.com/ethereum/go-ethereum/wiki/geth)
- [Infura: A public API Interface for Ethereum](https://infura.io/)

#### Key Developer Tools
- [Hyperledger Besu: an open source,  enterprise-grade, Java-based Ethereum client](https://pegasys.tech/solutions/hyperledger-besu/)
- [Parity: A Rust-based Ethereum client](https://www.parity.io/)
- [Metamask: Chrome Extension for Ethereum](https://metamask.io/)
- [Remix: an in-browser IDE for Smart Contract Development](https://remix.ethereum.org/#optimize=false&evmVersion=null)
- [Truffle: A Blockchain Development Framework](https://www.trufflesuite.com/)
- [Truffle Ganache: A Private Testnet for Blockchain Development](https://www.trufflesuite.com/ganache)
- [Web3.js: Javascript Library for Ethereum + front-end integration](https://web3js.readthedocs.io/en/v1.2.9/)
- [IPFS website: Distributed File Storage Mechanism](https://ipfs.io/)
- [Swarm documentation: Distributed File Storage within Geth](https://swarm-guide.readthedocs.io/en/latest/introduction.html)

#### Geth
- [Getting started with Geth](https://geth.ethereum.org/docs/getting-started)
- [Setup Your Own Private Proof of Authority Ethereum Network with Geth](https://hackernoon.com/setup-your-own-private-proof-of-authority-ethereum-network-with-geth-9a0a3750cda8)
- ["Proof of Authority Chains," Parity Technologies](https://openethereum.github.io/wiki/Proof-of-Authority-Chains)
- ["Proof-of-Authority Tutorial," Parity Technologies](https://openethereum.github.io/wiki/Demo-PoA-tutorial.html)
- ["Using Puppeth to Manually Create an Ethereum Proof-of-Authority Clique Network using AWS," Collin Cusce](https://medium.com/@collin.cusce/using-puppeth-to-manually-create-an-ethereum-proof-of-authority-clique-network-on-aws-ae0d7c906cce)
- [Clique PoA Protocol Details, Péter Szilágyi & Ethereum Foundation](https://github.com/ethereum/EIPs/issues/225)
- [Cliquebait Repo, from FOAM](https://github.com/f-o-a-m/cliquebait)

### Development Frameworks and Environment

#### MetaMask
- [Metamask.io](https://metamask.io/)
- [Metamask developer documentation](https://docs.metamask.io/guide/)

#### Ganache CLI
- [Ganache-cli on npm](https://www.npmjs.com/package/ganache-cli)

#### Truffle
- [Truffle Boxes](https://www.trufflesuite.com/boxes)
- [Creating a Project with Truffle ](https://www.trufflesuite.com/docs/truffle/getting-started/creating-a-project)

#### Ganache GUI
- [Download Ganache GUI](https://www.trufflesuite.com/ganache)
- [Ganache Documentation](https://www.trufflesuite.com/docs/ganache/overview)

### Solidity Fundamentals

#### Data Types and Variables
- [Solidity Docs - Types](https://solidity.readthedocs.io/en/latest/types.html) 
- [Solidity Docs - Contract Types](https://solidity.readthedocs.io/en/latest/types.html#contract-types)
 
#### Functions
- [Solidity docs - Functions](https://solidity.readthedocs.io/en/latest/contracts.html#functions)
- [Solidity docs - Function Types](https://solidity.readthedocs.io/en/latest/types.html?highlight=function%20types#function-types)

#### Storage and Memory
- [Difference between memory and storage](https://ethereum.stackexchange.com/questions/1232/difference-between-memory-and-storage)
- [Storage, Memory and the Stack](https://solidity.readthedocs.io/en/latest/introduction-to-smart-contracts.html#storage-memory-and-the-stack)
- [Data location -- Solidity Docs](https://solidity.readthedocs.io/en/latest/types.html#data-location)

#### Contract Structure
- [Structure of a Contract](https://solidity.readthedocs.io/en/develop/structure-of-a-contract.html)
- [Smart contracts as a State Machine](https://solidity.readthedocs.io/en/develop/common-patterns.html?#state-machine)
- [Solidity Assembly Code](https://solidity.readthedocs.io/en/latest/assembly.html)

#### Reading Smart Contracts with Remix
- [SimpleStorage.sol](https://gist.github.com/ConsenSys-Academy/6d93a805ce0e90d8a793a4eb6e69b4c5#file-simplestorage-sol)
- [Solidity by Example - Solidity Docs](https://solidity.readthedocs.io/en/latest/solidity-by-example.html)

#### Smart Contract ABI
- [Solidity Docs - ABI](https://solidity.readthedocs.io/en/latest/abi-spec.html)
- [What is the ABI and why is it needed to interact with contracts](https://ethereum.stackexchange.com/questions/234/what-is-an-abi-and-why-is-it-needed-to-interact-with-contracts)

#### Events and Logs
- [Technical introduction to Events and Logs in Ethereum by Joseph Chow, Consensys Media](https://media.consensys.net/technical-introduction-to-events-and-logs-in-ethereum-a074d65dd61e)
- [Events - Solidity Docs](https://solidity.readthedocs.io/en/latest/contracts.html#events)
- [Listening to events with web3.js](https://web3js.readthedocs.io/en/v1.2.9/web3-eth-subscribe.html?highlight=events#subscribe-logs) 
- [Listening to events via the contract object](https://web3js.readthedocs.io/en/v1.2.9/web3-eth-contract.html#contract-events)

#### Factory Contracts
- [Manage several contracts with Factories](https://ethereumdev.io/interact-with-other-contracts-from-solidity/)
- [EIP20.sol by ConsenSys](https://github.com/ConsenSys/Tokens/blob/master/contracts/eip20/EIP20.sol)
- [EIP20Factory.sol by ConsenSys](https://github.com/ConsenSys/Tokens/blob/master/contracts/eip20/EIP20Factory.sol)

### Writing Smart Contracts

#### Introductory Smart Contracts
- [Truffle Pet Shop Tutorial](https://www.trufflesuite.com/tutorials/pet-shop)

#### Inter-Contract Execution
- [BaseCaller.sol](https://gist.github.com/critesjosh/50eb7f243cf960ebf6240fae52c14e63)
- [ContextSwitcher.sol](https://gist.github.com/ConsenSys-Academy/de1b2000f3682f0cfba784d0cb5400e7)
- [Difference between call, callcode and delegatecall - stackexchange](https://ethereum.stackexchange.com/questions/3667/difference-between-call-callcode-and-delegatecall)
- [Interactions between contracts](https://dappsforbeginners.wordpress.com/tutorials/interactions-between-contracts/)

#### Inheritance
- [Inheritance in Solidity](https://ethereumdev.io/inheritance-in-solidity-contracts-are-classes/)
- [Inheritance, from the Solidity Docs](https://solidity.readthedocs.io/en/develop/contracts.html#inheritance)
- [Abstract contracts](https://solidity.readthedocs.io/en/latest/contracts.html#abstract-contracts)
- [Interfaces](https://solidity.readthedocs.io/en/latest/contracts.html#interfaces)

#### Libraries and the Ethereum Package Manager
- [Library Driven Development inSolidity](https://medium.com/aragondec/library-driven-development-in-solidity-2bebcaf88736)
- [Libraries in the Solidity Docs](https://solidity.readthedocs.io/en/develop/contracts.html#libraries)
- [Linking to deployed libraries with Truffle migrations](https://www.trufflesuite.com/docs/truffle/getting-started/running-migrations#deployer-link-library-destinations-)
- [What are the steps to compile and deploy a library in solidity?](https://ethereum.stackexchange.com/questions/6927/what-are-the-steps-to-compile-and-deploy-a-library-in-solidity)
- [Package Management with EthPM in Truffle](https://www.trufflesuite.com/docs/truffle/getting-started/package-management-via-ethpm)
- [EthPM: Reusable Smart Contract Packages](https://medium.com/coinmonks/ethpm-smart-contract-packages-for-developers-81c77481c491)

### References
- [Smart Contracts by Nick Szabo](https://drive.google.com/file/d/1fQpwlpWToDyBMyBhZDobS29Szn4xpXeH/view)  
- [Smart Contracts: Building Blocks for Digital Markets](https://www.fon.hum.uva.nl/rob/Courses/InformationInSpeech/CDROM/Literature/LOTwinterschool2006/szabo.best.vwh.net/smart_contracts_2.html)
- [Ethereum: A Next Generation Smart Contract and Decentralized Application Platform](https://ethereum.org/whitepaper/)
- [Ethereum: A Secure Decentralised Generalised Transaction Ledger](https://ethereum.github.io/yellowpaper/paper.pdf)

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
