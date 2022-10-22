# Aave-dune-analysis
This is description of the Have analysis dashboard on dune analytics platform

## Aave liqidity protocol

**Methodology**

In this dashboard, we will be focusing on the borrowing and lending side of Aave and should cover topics such as:

Breakdown of deposit supply and borrowing by tokens:

1. Aave v2 total borrows on ethereum.

2. Aave v2 total deposits on ethereum.

3. Aave v2 deposit and borrowing over time.

4. Deposit supply for each asset.

5. Borrowing amount for each asset.

Number of wallets borrowing and lending:
1.Aave v2 on Etheruem daily user activity
2. Total Unique borrowers
3. Total Unique depositors

`SELECT  
SUM(BORROWED_USD) AS AAVE_V2_Total_Borrow
FROM ethereum.aave.ez_borrows
  WHERE AAVE_VERSION = 'Aave V2'`
