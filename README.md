# solana-awesome

A comprehensive, factual resource hub for anyone interested in learning about the Solana blockchain and its underlying technology.

- [Introduction and Overview](#introduction-and-overview)
- [Compression](#compression)
- [Solana Mobile](#solana-mobile)
- [Opinion and Essays](#opinion-and-essays)
- [Technical Deep Dives](#technical-deep-dives)
- [Developer Resources](#developer-resources)
- [Case Studies and Analysis](#case-studies-and-analysis)
- [The Future of Solana](#the-future-of-solana)
- [Accessible Explainers](#accessible-explainers)

## Introduction and Overview

| Title                                  | Type    | Author   | Link                                                                                                     | Description                                                                            |
| :------------------------------------- | :------ | :------- | :------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------- |
| The Solana Programming Model           | Article | 0xIchigo | [Link](https://www.helius.dev/blog/the-solana-programming-model-an-introduction-to-developing-on-solana) | This article explores Solana's architecture, account model, and transaction mechanics. |
| Programming on Solana, An Introduction | Article | Paul X   | [Link](https://paulx.dev/blog/2021/01/14/programming-on-solana-an-introduction/)                         | Introductory post on Solana programming.                                               |

## Compression

| Title                                                                      | Type          | Author(s)                                                  | Link                                                                                                                               | Description                                                                                               |
|----------------------------------------------------------------------------|---------------|------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------|
| Compressing Digital Assets with Concurrent Merkle Trees                    | Whitepaper    | Jarry Xiao, Noah Gundotra, Austin Adams, Anatoly Yakovenko | [Link](https://drive.google.com/file/d/1BOpa5OFmara50fTvL0VIVYjtg-qzHCVc/view)                                                     | The theory behind state compression                                                                       |
| State Compression                                                          | Documentation | Solana Foundation                                          | [Link](https://solana.com/docs/advanced/state-compression)                                                                         | The official documentation on state compression                                                           |
| Exploring NFT Compression on Solana                                        | Article       | Mert Mumtaz                                                | [Link](https://www.helius.dev/blog/solana-nft-compression)                                                                         | Learn how to work with NFT Compression on Solana                                                          |
| All You Need to Know About State Compression on Solana                     | Article       | 0xIchigo                                                   | [Link](https://www.helius.dev/blog/all-you-need-to-know-about-compression-on-solana)                                               | Learn about state compression, compressed NFTs (cNFTs), as well as how to fetch, mint, or transfer them   |
| ZK Compression                                                             | Documentation | Helius x Light Protocol                                    | [Link](https://www.zkcompression.com/)                                                                                             | A new primitive aimed at reducing state costs by orders of magnitude                                      |
| State Compression and Compressed NFTs                                      | GitHub Repo   | solana-developers                                          | [Link](https://github.com/solana-developers/compressed-nfts)                                                                       | Example code to use compressed NFTs on Solana                                                             |
| How to Mint Solana Compressed NFTs (cNFTs) with TypeScript                 | Article       | kishi.sol                                                  | [Link](https://medium.com/@KishiTheMechanic/how-to-mint-solana-compressed-nfts-cnfts-with-typescript-be9d0fa7ce30)                 | A step-by-step guide on minting cNFTs with TypeScript                                                     |
| Creating Compressed NFTs with JavaScript                                   | Article       | Solana Foundation                                          | [Link](https://solana.com/developers/guides/javascript/compressed-nfts)                                                            | A step-by-step guide on creating trees, minting, reading, and transferring cNFTs in JavaScript/TypeScript |
| Tips for Minting Multiple Compressed NFTs (cNFTs) Simultaneously on Solana | Article       | kishi.sol                                                  | [Link](https://medium.com/@KishiTheMechanic/tips-for-minting-multiple-compressed-nfts-cnfts-simultaneously-on-solana-4e01e06bae00) | Tips for minting multiple cNFTs simultaneously                                                            |

## Solana Mobile

| Title                                             | Type          | Author(s)          | Link                                                                                  | Description                                                                     |
|---------------------------------------------------|---------------|--------------------|---------------------------------------------------------------------------------------|---------------------------------------------------------------------------------|
| Solana Mobile Stack                               | Documentation | Solana Mobile Team | [Link](https://docs.solanamobile.com/)                                                | Comprehensive resources for mobile development on Solana                        |
| Mobile dApp Architecture                          | Documentation | Mike Sulistio      | [Link](https://docs.solanamobile.com/getting-started/mobile-dapp-architecture)        | An overview of mobile dApp architecture with the Mobile Wallet Adapter protocol |
| Publishing Solana Mobile Apps: A How to Guide     | Article       | 0xSolanaGirl       | [Link](https://www.helius.dev/blog/publishing-solana-mobile-apps)                     | The necessary steps and resources to publish on the Solana Mobile dApp Store    |
| Token Gating on Solana - A Solana Mobile Tutorial | Article       | 0xSolanaGirl       | [Link](https://www.helius.dev/blog/token-gating-on-solana-mobile-tutorial)            | Learn how to create token-gating experiences using the Saga Genesis Token       |
| Build a cNFT Minter Mobile App in Under 5 Minutes | Article       | Anam Ansari        | [Link](https://www.helius.dev/blog/build-a-cnft-minter-mobile-app-in-under-5-minutes) | A tutorial covering how to build a cNFT minting Android application             |
| Solana Mobile Tutorial Apps                       | GitHub Repo   | solana-mobile      | [Link](https://github.com/solana-mobile/tutorial-apps)                                | A collection of tutorial apps showcasing the Solana Mobile Stack (SMS)          |

## Opinion and Essays

| Title                   | Type    | Author          | Link                                                               | Description                                           |
| :---------------------- | :------ | :-------------- | :----------------------------------------------------------------- | :---------------------------------------------------- |
| Solana Summer           | Article | Packy McCormick | [Link](https://www.notboring.co/p/solana-summer)                   | Comprehensive and engaging read about Solana's story. |
| The Year Solana Blew Up | Article | Ryan Shea       | [Link](https://writing.ry.sh/the-year-solana-blew-up-6d50cccb4615) | Must-read for those interested in Solana.             |
| Why Solana              | Article | Mert Mumtaz     | [Link](https://www.mertimus.com/p/why-solana)                      | A personal perspective on building on Solana.         |

## Technical Deep Dives

| Title                                          | Type       | Author            | Link                                                                                                                   | Description                                                                      |
| :--------------------------------------------- | :--------- | :---------------- | :--------------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------- |
| Architecture for a High Performance Blockchain | Whitepaper | Anatoly Yakovenko | [Link](https://solana.com/solana-whitepaper.pdf)                                                                       | Proposal of a new blockchain architecture.                                       |
| Proof of History Primer                        | Article    | Shinobi Systems   | [Link](https://www.shinobi-systems.com/primer.html)                                                                    | Easily digestible deep-dive into Proof of History.                               |
| Transaction Processing on Solana               | Article    | Jito Labs         | [Link](https://www.jito.wtf/blog/solana-validator-101-transaction-processing/)                                         | Deep dive into validator internals and transaction processing.                   |
| Solana Internals                               | Article    | Sec3              | [Link](https://www.sec3.dev/blog/solana-internals-part-1-what-are-the-native-on-chain-programs-and-why-do-they-matter) | Series deep-diving into Solana internals.                                        |
| Mobile dApp Architecture                       | Docs       | Mike Sulistio     | [Link](https://docs.solanamobile.com/getting-started/mobile-dapp-architecture)                                         | An overview of mobile dApp architecture with the Mobile Wallet Adapter protocol. |

## Developer Resources

| Title                                   | Type     | Author               | Link                                                             | Description                                                            |
| :-------------------------------------- | :------- | :------------------- | :--------------------------------------------------------------- | :--------------------------------------------------------------------- |
| Create Your First Solana dApp           | Tutorial | Loris Leiva          | [Link](https://lorisleiva.com/create-a-solana-dapp-from-scratch) | Easy tutorial on writing Solana programs.                              |
| The Solana Cookbook                     | Docs     | Solana Cookbook Team | [Link](https://solanacookbook.com/#contributing)                 | Cookbook for Solana developers.                                        |
| Solana Mobile Developer Docs            | Docs     | Solana Mobile Team   | [Link](https://docs.solanamobile.com/)                           | Comprehensive resources for mobile development on Solana.              |
| Skeet - TypeScript Serverless Framework | Docs     | Skeet Dev            | [Link](https://skeet.dev/)                                       | Open-Source TypeScript Serverless Framework for creating Solana dApps. |
| solv - Solana Validator Tool            | Docs     | Epics DAO            | [Link](https://solv.epics.dev/)                                  | Open-Source Tool for easy running Solana Validator.                    |

## Case Studies and Analysis

| Title                          | Type    | Author        | Link                                                                                          | Description                                                       |
| :----------------------------- | :------ | :------------ | :-------------------------------------------------------------------------------------------- | :---------------------------------------------------------------- |
| Firedancer Reliability Efforts | Article | Jump Crypto   | [Link](https://jumpcrypto.com/writing/firedancer-reliability/)                                | Analysis of past Solana outages and Firedancer's role.            |
| Transaction Confirmations      | Article | Jstarry       | [Link](https://jstarry.notion.site/Transaction-confirmation-d5b8f4e09b9c4a70a1f263f82307d7ce) | Deep dive into the transaction confirmation process.              |
| Key custody on iOS             | Article | Mike Sulistio | [Link](https://docs.solanamobile.com/blog/ios-wallet-signing)                                 | Deep dive into the patterns and challenges of key custody on iOS. |

## The Future of Solana

| Title                                          | Type    | Author(s)          | Link                                                         | Description                                                                                                                    |
|------------------------------------------------|---------|--------------------|--------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------|
| What is the State Growth Problem on Solana     | Article | Anatoly Yakovenko  | [Link](https://x.com/aeyakovenko/status/1796569211273445619) | A Twitter article covering the rapid growth of Solana's state and potential solutions                                          |
| Asynchronous Program Execution (APE) in Solana | Article | Anatoly Yakovenko  | [Link](https://x.com/aeyakovenko/status/1804937522998591577) | A Twitter article covering asynchronous execution and the goal of running the vote program independently of all other programs |

## Accessible Explainers

| Title                                                                      | Type    | Author    | Link                                                                                                                               | Description                                            |
| :------------------------------------------------------------------------- | :------ | :-------- | :--------------------------------------------------------------------------------------------------------------------------------- | :----------------------------------------------------- |
| A Dummy’s Guide to Solana’s Architecture                                   | Article | Anvit     | [Link](https://anvit.hashnode.dev/a-dummys-guide-to-solana-architecture)                                                           | An overview of Solana's architecture.                  |
| Local Fee Markets on Solana                                                | Thread  | 7Layer    | [Link](https://twitter.com/7LayerMagik/status/1615569374647287808)                                                                 | Deep dive into what fee markets are and how they work. |
| How to Mint Solana Compressed NFTs (cNFTs) with TypeScript                 | Article | kishi.sol | [Link](https://medium.com/@KishiTheMechanic/how-to-mint-solana-compressed-nfts-cnfts-with-typescript-be9d0fa7ce30)                 | A step-by-step guide on how to mint cNFTs.             |
| Implementing "Sign In With Solana"(SIWS)                                   | Article | kishi.sol | [Link](https://medium.com/@KishiTheMechanic/implementing-sign-in-with-solana-siws-ce35dadeda31)                                    | A step-by-step guide on how to implement SIWS.         |
| Tips for Minting Multiple Compressed NFTs (cNFTs) Simultaneously on Solana | Article | kishi.sol | [Link](https://medium.com/@KishiTheMechanic/tips-for-minting-multiple-compressed-nfts-cnfts-simultaneously-on-solana-4e01e06bae00) | Tips for minting multiple cNFTs simultaneously.        |
