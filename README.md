# Awesome Account Abstraction
An awesome list of resources for designing, building, and using account abstraction wallets on Ethereum and EVM blockchains.

Pull requests are welcome! 🤝

## Contents
1. [Overview](#overview)
2. [Required Reading](#required-reading)
3. [AA Wallets & SDKs](#aa-wallets-&-sdks)
4. [4337 Implementations](#4337-implementations)
5. [Other Resources](#other-resources)

## Overview
Account Abstraction (AA) is the movement within Ethereum and EVM-compatible chains to improve transaction user experience by using smart contract wallets as primary accounts as opposed to externally-owned accounts (EOAs). [EIP-4337](https://eips.ethereum.org/EIPS/eip-4337) is the leading standard for implementing AA wallets, which has the benefit of not needing consensus-layer protocol changes, improves UX through bundled transactions, allows free/subsidized/token-paid gas costs, and supports optional privacy and signature enchancing features. 

### 🙂 Required Reading
- [EIP-4337](https://eips.ethereum.org/EIPS/eip-4337) - The latest and most-likely-to-be-adopted EIP for account abstraction
- [Vitalik's Road to Account Abstraction](https://notes.ethereum.org/@vbuterin/account_abstraction_roadmap) - Account abstraction history on Ethereum and reasoning how we got to EIP-4337

## AA Wallets & SDKs
- [Biconomy](https://www.biconomy.io/sdk) - SDK for creating AA wallets and submitting txs
- [StackUp](https://www.stackup.sh/) - Account abstraction infrastructure and bundler services
- [Candide Wallet](https://www.candidewallet.com/) - Consumer wallet built on account abstraction and Safe DAO (prev Gnosis Safe)
- [Soul Wallet](https://twitter.com/soulwallet_eth) - Consumer wallet launched at ETHBogotá 

## 4337 Implementations
- [Biconomy's 4337 implementation](https://github.com/bcnmy/scw-contracts/tree/master/contracts/smart-contract-wallet/aa-4337)
- [Soul Wallet's 4337 implementation](https://github.com/proofofsoulprotocol/soul-wallet-contract/blob/main/contracts/SmartWallet.sol)
- [Candide Wallet's 4337 implementation](https://github.com/candidelabs/CandideWalletContracts)
- [Eth Inifitism's 4337 implementation](https://github.com/eth-infinitism/account-abstraction/tree/develop/contracts)

## Other Resources
- [Smart Contract Wallet Overview from 1kx](https://medium.com/1kxnetwork/wallets-91c7c3457578)
- [Open Zeppelin's EIP-4337 – Ethereum Account Abstraction Audit](https://blog.openzeppelin.com/eth-foundation-account-abstraction-audit/)

## Contribute
Contributions welcome! Open a PR!

## License
L<icensed under the MIT license, which you can find in the MIT-LICENSE.txt file.

All graphical assets are licensed under the Creative Commons Attribution 3.0 Unported License.
