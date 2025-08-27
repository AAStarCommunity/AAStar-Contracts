# AAStar Contracts
这里汇集所有的AAStar合约和基础测试，为不同链提供已部署的地址常量和链上验证。

## AirAccount
We inhereted from Alchemy Light Account to fininsh a double signature(finger-print and TEE) contract account with EOA support(EIP7702).

## What is AirAccount?
Accounts also used to store users' valuable assets (cash, securities, or Tokens, NFTs, etc.), there is a significant difference between bank accounts and blockchain accounts: one is centralized custody, and the other is self-custody.

The biggest gap between the two is that banks have a complete security system and monitoring measures.

AirAccount provide this service in decentralied way based on SDSS(Standardized Decentralized Service System), just from 15 steps to 4 steps(2 one tiem setup steps).

## History
We launched the initial version in [Estanbul Hackathon](https://ethglobal.com/showcase/airaccount-swqix).
We fininshe v0.1 in [Zu.coffee](https://zu.coffee) and [COS72](https://ethglobal.com/showcase/cos72-i8w6f) to launch transaction with your finger print and seamless gasless.

## Roadmap
1. BLS aggregation of decentralized validator siganature and verify in pre-compiled EIP2537.
2. NFT with ERC20 balance to pay gas seamlessly on contract account
3. EOA binding and pay gas in contract account's ERC20 balance
4. Community, friends and guardians as social recovery
5. Shops and PNTs support in auto apporovment and auto allocation
6. more...
