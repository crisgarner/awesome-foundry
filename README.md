# Awesome Foundry

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![Telegram Chat](https://img.shields.io/endpoint?color=neon&url=https%3A%2F%2Ftg.sumanjay.workers.dev%2Ffoundry_rs)](https://t.me/foundry_rs) [![Telegram Chat](https://img.shields.io/endpoint?color=neon&url=https%3A%2F%2Ftg.sumanjay.workers.dev%2Ffoundry_support)](https://t.me/foundry_support)

[//]: # ([![Track Awesome List]&#40;https://www.trackawesomelist.com/badge.svg&#41;]&#40;https://www.trackawesomelist.com/avelino/awesome-go/&#41;)

Foundry is a blazing fast, portable and modular toolkit for Ethereum application development written in Rust. [Install Foundry here](https://getfoundry.sh).

<img align="center" src="https://mirror.xyz/_next/image?url=https%3A%2F%2Fimages.mirror-media.xyz%2Fpublication-images%2Fkt99mFtZZ1Gl2ZbWGNI3J.png&w=3840&q=90" alt="awesome-foundry" title="awesome-foundry" />


> A curated list of awesome Foundry resources, tutorials, tools and libraries. Inspired by [awesome-go](https://github.com/avelino/awesome-go).


### Contributing 

Please take a quick view at the [contribution guidelines](https://github.com/crisgarner/awesome-foundry/blob/main/CONTRIBUTING.md) first. 

[//]: # (Thanks to all [contributors]&#40;https://github.com/crisgarner/awesome-foundry/graphs/contributors&#41;; you rock!)

#### *If you see a package or project here that is no longer maintained or is not a good fit, please submit a pull request to improve this file. Thank you!*

## Content

- [Awesome Foundry](#awesome-foundry)
- [Tools](#tools)
- [Libraries](#libraries)
- [Tutorials](#tutorials)
- [Projects Using Foundry](#projects-using-foundry)

**[⬆ back to top](#awesome-foundry)**

## Tools
Frameworks, plugins and utilities for Foundry.
- [Foundryup](https://github.com/foundry-rs/foundry/tree/master/foundryup) - Update or revert to a specific Foundry branch with ease.
- [Foundry Hardhat](https://github.com/foundry-rs/hardhat) - Hardhat plugins to use foundry tools in hardhat environments.
- [Foundry Template](https://github.com/ZeframLou/foundry-template) - A template for a Foundry project.
- [Forge Template](https://github.com/FrankieIsLost/forge-template) - A template for quickly getting started with forge.
- [Forge Standard Library](https://github.com/foundry-rs/forge-std/) - Collection of helpful contracts for use with forge and foundry.
- [Forge GHA](https://github.com/foundry-rs/foundry-toolchain) - Simple Github Actions workflow to run forge test.
- [Forge Replit](https://replit.com/@wilsonc/VanillaForge) - Run Forge in the browser, vanilla setup.
- [Forge Snippets](https://github.com/crisgarner/VSCodeForgeSnippets) - VS Code Snippets for Forge.
- [Foundrydeploy](https://github.com/joshieDo/foundrydeploy) - Limited scripting (declarative?) language to implement a basic deployment pipeline using foundry. 
- [Foundry Docgen](https://github.com/ZeframLou/foundry-docgen) - A basic tool for generating markdown docs for a Foundry project using existing NatSpec comments in the contracts.
- [Foundry Hardhat Template](https://github.com/foundry-rs/hardhat-foundry-template) - Template repository for getting started quickly with Hardhat and Foundry in one project.
- [Foundry Vyper](https://github.com/0xKitsune/Foundry-Vyper) -  A Foundry template to compile and test Vyper contracts.
- [Foundry Starter Kit](https://github.com/smartcontractkit/foundry-starter-kit) - Foundry Starter Kit is a repo that shows developers how to quickly build, test, and deploy smart contracts with one of the fastest frameworks out there.
- [Femplate](https://github.com/abigger87/femplate/) - Robust Template for Foundry Projects

## Libraries
Solidity libraries or utilities that use Foundry.
- [Solmate](https://github.com/transmissions11/solmate) - Modern, opinionated, and gas optimized building blocks for smart contract development.
- [Chain Claim](https://github.com/botdad/chain-claim) - Solidity lib and helper scripts for providing claim code generation and on chain verification of a claim.
- [Playpen](https://github.com/ZeframLou/playpen) - Set of modern, gas optimized staking pool contracts.
- [TokenMigrator](https://github.com/ZeframLou/token-migrator) - A simple contract for migrating from an old ERC20 token to a new ERC20 token.
- [VestedERC20](https://github.com/ZeframLou/vested-erc20) - A wrapper ERC20 token that linearly vests an underlying ERC20 token to its holders.
- [forge-gas-snapshot](https://github.com/marktoda/forge-gas-snapshot) - A flexible gas snapshotting library for forge tests.
- [lil web3](https://github.com/m1guelpf/lil-web3/) - Small, focused, utility-based smart contracts.
- [RollCall](https://github.com/withtally/rollcall) - Rollup Governance Libraries.
- [Forge Optimism](https://github.com/tarrencev/forge-optimism) - Forge Optimism is a collection of helpful contracts for use with forge and foundry on Optimism.
- [Yearn Strategy Foundry Mix](https://github.com/storming0x/foundry_strategy_mix) - Basic Solidity Smart Contract for creating your own Yearn Strategy.
- [Foundry-Hardhat-Diamonds](https://github.com/Timidan/Foundry-Hardhat-Diamonds)- Sleek EIP2535 Diamond deployments on the go with foundry
- [Founndry Lens Protocol](https://github.com/memester-xyz/lens-protocol#foundry-setup) - Lens Protocol fork that supports Foundry. 
- [XChain](https://github.com/zobront/xchain) - Cross chain call library for Solidity & Foundry.
- [Solenv](https://github.com/memester-xyz/solenv) - A dotenv parser for Solidity & Foundry.
- [surl](https://github.com/memester-xyz/surl/) - HTTP library for Foundry tests in Solidity based on curl.
- [unix](https://github.com/abigger87/unix) - A lightweight, extensible Foundry library for shell scripting.
- [Chainlink Brownie Contracts](https://github.com/smartcontractkit/chainlink-brownie-contracts) - This repository is a slimmed down version of Chainlink's official repo. It clones only the Chainlink contracts folder and the repo automatically updates every time there is a new NPM release.
- [Upgradeable Contracts With OpenZeppelin and Foundry](https://github.com/jordaniza/OZ-Upgradeable-Foundry) - A minimal set of contracts showing how to implement UUPS and Transparent Upgradeable Proxy contracts using foundry, along with testing and deployment with Forge Script.
- [Foundry Upgrades](https://github.com/odyslam/foundry-upgrades) - Helper smart contracts to deploy and manage upgradeable contracts on Ethereum. 

## Tutorials
- [Getting Started by Crisgarner](https://mirror.xyz/crisgarner.eth/BhQzl33tthkJJ3Oh2ehAD_2FXGGlMupKlrUUcDk0ALA) - Short intro tutorial for getting started. 
- [Getting Started by Wilson](https://w.mirror.xyz/mOUlpgkWA178HNUW7xR20TdbGRV6dMid7uChqxf9Z58) - Extended tutorial with information about testings and logging.
- [Getting Started by What The Func?](https://youtu.be/wqFnif_6Mbc) - Video tutorial.
- [How to Foundry with Brock Elmore](https://www.youtube.com/watch?v=Rp_V7bYiTCM) - YouTube live code tutorial on how to get started with Foundry.
- [Foundry Book](https://book.getfoundry.sh/) - A book on all things Foundry.
- [Mainnet Forking](https://mirror.xyz/susheen.eth/bRCzT2QLdNINMVk8251udkfjHW_T9ascCQ1DV9hURz0) - This article teaches how to run a locally simulate a swap on Uniswap.
- [Ethernaut x Foundry](https://github.com/ciaranmcveigh5/ethernaut-x-foundry) - Ethernaut puzzles solved & tested with foundry.
- [Damn Vulnerable Defi - Foundry Version](https://github.com/nicolasgarcia214/damn-vulnerable-defi-foundry) - The Damn Vulnerable Defi CTF using Foundry.
- [Getting Started (Chinese)](https://learnblockchain.cn/article/3502) - Getting started tutorial on Chinese.
- [Foundry vs Hardhat](https://chainstack.com/foundry-hardhat-differences-performance/) - Differences in performance and developer experience.
- [Smart Contract Development with Foundry](https://www.youtube.com/watch?v=uelA2U9TbgM) - Extended video tutorial on Foundry covering tests, deployments, cast usage, deploying to a live network.
- [DeFiHackLabs](https://github.com/SunWeb3Sec/DeFiHackLabs) - Reproduce DeFi hack incidents using Foundry. 
- [DeFiVulnLabs](https://github.com/SunWeb3Sec/DeFiVulnLabs) - To learn common smart contract vulnerabilities using Foundry. 



## Projects Using Foundry
- [OpenSea Seaport](https://github.com/ProjectOpenSea/seaport) - Seaport is a new marketplace protocol for safely and efficiently buying and selling NFTs.
- [MapleLoan](https://github.com/maple-labs/loan) - Set of contracts to facilitate on-chain Loans between Maple Finance Pools and institutional borrowers.
- [Cryptex Finance](https://github.com/cryptexfinance/contracts) - Index token that tracks the total cryptocurrency market capitalization. (Optimism version uses Foundry tests).
- [Gov of Venice](https://github.com/pentagonxyz/gov-of-venice) - Governance of Venice is a new paradigm in DAO governance, attempting to standardise the existence of functional groups within DAOs (Guilds) in terms of how they participate in the Governance process of different DAOs. 
- [Beefy Finance](https://github.com/beefyfinance/beefy-contracts) - Official repo for strategies and vaults from the Beefy yield optimizer.
- [Tokenlon](https://github.com/consenlabs/tokenlon-contracts) - Tokenlon is a decentralized exchange and payment settlement protocol.

**[⬆ back to top](#awesome-foundry)**
