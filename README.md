---
description: An overview of the SigmaFi lending protocol
cover: .gitbook/assets/sigmafi-banner.svg
coverY: 26
---

# Introduction

Sigma Finance ([SigmaFi](https://sigmafi.app/#/)) allows anyone with an Ergo wallet to request a loan. Each request specifies the loan amount, the length (term) of the loan and the amount of interest of the loan.

Collateral guarantees SigmaFi loans. If the loan is not repaid by the time the term ends, the lender can take the collateral as payment. Given the volatility of cryptocurrencies, loans need to be over-collateralized to get funded. For example, a loan of 100 SigUSD might need ERG worth 150 SigUSD for someone to lend the money.

A new loan request creates a smart contract that specifies the terms of the loan. The smart contract holds the collateral and offers the loan at the SigmaFi website. If someone accepts the terms of the loan, they can lend the money through the website. The person making the request receives the loan. The lender will either be repaid, with interest, or take the collateral.

SigmaFi is an example of decentralized finance (DeFi). It allows people to create and fund loan requests person to person (P2P). No banks or other intermediatory is necessary.

SigmaFi leverages the extended unspent transaction output (eUTXO) model to create these loans. All SigmaFi contracts are open-source and free to build upon. Developers are free to use SigmaFi contracts as building blocks for their applications.

Website: [https://sigmafi.app/](https://sigmafi.app/)\
\
SigmaFi Contracts: [https://github.com/K-Singh/Sigma-Finance](https://github.com/K-Singh/Sigma-Finance)\
\
SigmaFi Frontend: [https://github.com/capt-nemo429/sigmafi-ui](https://github.com/capt-nemo429/sigmafi-ui)
