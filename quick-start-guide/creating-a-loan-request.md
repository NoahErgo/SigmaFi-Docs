# Creating a Loan Request

1. With your wallet connected, click on "NEW LOAN REQUEST"

<figure><img src="../.gitbook/assets/Connect sigmafi.png" alt=""><figcaption></figcaption></figure>

2. Specify all of the following parameters of your loan request:
   1. The asset you wish to borrow.
   2. The length of the repayment window, after which your collateral can be liquidated if you do not repay the lender. This can be specified in hours, days, or months based on an average of 2 minute block time.
   3. The interest amount as a fixed percentage of the amount you are requesting to borrow. This will be included.
   4. The asset(s) you are putting up as collateral to the lender in case you fail to repay before the repayment window has expired.

<figure><img src="../.gitbook/assets/Screen Shot 2023-04-16 at 2.31.57 PM.png" alt=""><figcaption></figcaption></figure>

3. Click "CONFIRM" and then in the Nautilus pop-up window, sign the transaction

<figure><img src="../.gitbook/assets/Screen Shot 2023-04-16 at 2.38.02 PM.png" alt=""><figcaption></figcaption></figure>

This will send your collateral, ERG for transaction fee, and ERG for the UI fee.

4. Wait for transaction confirmation - That's it! Your loan request will then appear in the market section of the SigmaFi UI.
5. Monitor the loan repayment window. If you do not wish to have your collateral liquidated, you must be sure to repay the original loan amount, and interest promised, prior to the end of the loan term. If you fail to repay the debt, your collateral can be liquidated by the lender at any time.
