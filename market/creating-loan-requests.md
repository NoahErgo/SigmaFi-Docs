---
description: An overview of the Loan Request creation process
---

# Creating Loan Requests

<figure><img src="../.gitbook/assets/Screen Shot 2023-04-16 at 2.00.28 PM.png" alt=""><figcaption></figcaption></figure>

Borrowers can create a new loan request from the market tab. Here the user will specify which asset, and the amount of that asset, they wish to borrow. Currently the following assets are available to borrow:

* ERG
* SigUSD
* SigRSV
* Ergopad
* Paideia
* SPF

The borrower sets the term length of the loan. The borrower can choose a term length in units of hours, days, or months. The term length will also be displayed in blocks. **Borrowers should know that the term length in units of time is subject to fluctuation, as it is converted from estimated two minute block time. In unusual conditions block times can be drastically shorter or longer depending on mining difficulty.**

The borrower also sets the interest percentage. The interest amount will also be displayed in the units of the asset being requested.

**If the borrower does not repay the loan amount and its interest in this term window, the collateral they have selected can be liquidated by the lender and the borrower will not be able to reclaim it.** Currently, liquidations do not happen automatically and the lender must initiate a liquidation.

Borrowers should watch their repayment term closely if they wish to avoid liquidation. **Again, borrowers should note that the term length in units of time is subject to fluctuations due to varying block times.** Monitor your repayment term accordingly!

Finally, the borrower will also add the assets they wish to collateralize their loan request with. A single asset, or multiple assets can be used as collateral. Any Ergo native asset can be used as collateral, including governance tokens, NFTs, staking keys, LP tokens, vesting keys, etc. If the token exists on Ergo it can be used as collateral.

Borrowers will be charged a small UI fee and miner fee when they confirm their loan request.
