---
title: DeFi for Newbies
description: Your community guide into what Decentralized Finance is, and how it works!
published: true
date: 2022-06-27T02:04:19.462Z
tags: 
editor: markdown
dateCreated: 2022-06-22T23:25:19.037Z
---

# Decentralized Finance for Newbies

> This article is a work in progress. The information may not reflect the final state.
{.is-warning}

<!-- HI Felix! I did some editing, styling for you. - Togg -->

## What is "Decentralized Finance"
Decentralized Finance (DeFi) describes a financial system that is built in a "decentralized manner" (meaning no centralized server, or point of failure) and operated on or through a [Blockchain](https://en.wikipedia.org/wiki/Blockchain). This means, that in a DeFi application there is no intermediate between the different actors.

For instance on [Osmosis](https://osmosis.zone/), when a user makes a swap they are interacting *directly* with the liquidity providers without third party. To ensure a trustless process, DeFi applications use rules defined in either Smart Contracts (Ethereum) or natively in a blockchain (Cosmos SDK). The blockchain then enforces that every actor is complying to these rules. 

Possible DeFi applications are decentralized exchanges (Osmosis, Uniswap, Balancer) or money lending platforms (Mars Protocol, Curve, Aave, etc.).

## History of DeFi

<!-- Not Yet Completed -->

## Decentralized Exchanges
Nowadays most decentralized exchanges (DEXs) are operated through an Automated Market Maker (AMM). The AMM can be implemented through a smart contract or be baked directly into the blockchain and acts as liquidity reserve for the DEX. 

## Lending Platforms
Decentralized lending platforms are also a very popular DeFi implementation. They allow lenders to provider collateral and earn a APR (Annual Percentage Rate) on said collateral. Borrowers then can borrow money without any credibility score (Credit Score) a bank might ask for. With most DeFi loans, the borrower must usually deposit more collateral than the volume of the requested loan. This is called an "over-collateralized" loan. These types of loans are meant to offset the extreme price volatility of Cryptocurrencies.

## Risks/Vulnerabilities
DeFi applications also have risks which can affect the stored value (money) and in the worst cases, lead to total insolvency. One of the first potential vulnerabilities comes from bugs in the defined rules (smart contract or blockchain) which could empower actors to access funds they aren't supposed to access. This type of attack has happened several times in the past and is the biggest risk DeFi applications have.

> In October 2021 a bug in the Compound Smart Contract put [$160M at risk](https://decrypt.co/82499/compound-exploit-drains-21m-from-lending-protocol).
{.is-info}

> Osmosis suffered such a bug where 5M of funds in which $5M in liquidity was illicitly withdrawn.[^1]
{.is-info}

[^1]: "Cosmos-based DeFi Exchange Osmosis Hit by $5M Exploit," Sujith Somraaj, [Decrypt](https://decrypt.co/102300/cosmos-based-defi-exchange-osmosis-hit-by-5m-exploit)

Another potential vulnerability that DeFi applications are exposed to is when the blockchain on which the application runs, is itself attacked. Depending on the architechure of the chain the attack can be achieved in multiple different ways. However, the most common (and worried about, yet most unlikely) is through a "51% attack," where one entity controls the majority of the new blocks and therefore the whole network. If this happens it also controls all the funds that are stored in the network, including the DeFi application. Such an attack is unlikely on major blockchain networks such as, Ethereum, Bitcoin, Polygon, Cosmos Hub, etc.