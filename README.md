# fetacontract

FETA is a token on binance smart chain with a 9% reflect amount on each transaction. We
can calculate the burn and distributions from the following formulae.
● DistributeAmount=TransactionAmount x 0.09
● DistributePerAddress= (DistributeAmount / 3) * (AddressOwnedFETA / (∑TotalFETA -
(BurnedAddressOwnedFETA + CharityAddressOwnedFETA)))
● BurnedAmount=DistributeAmount / 3
● CharityAmount=DistributeAmount / 3
FETA - the Fun, Ethical Triangular Alt-coin.
In simple terms, for every FETA transaction 3% of the transaction is burned, 3% goes to the
charity wallet and 3% is shared among every holder in FETA, with each wallet receiving a
share proportional to its holding of FETA.
Below is an example of how these tokenomics work:
Address 0xFETAONE owns 3,000,000 FETA. A new wallet called 0xFETATWO buys 300,000
FETA on PancakeSwap, using 5% slippage and setting the FETA amount to a round number
(i.e. ideally ending in zero).
● The distribution amount from the 0xFETATWO transaction is 27,000, being 9% of the
total transaction. So 0xFETATWO receives 273,000.
● At this time there is 100,000,000 FETA that has been burnt and 12,000,000 FETA in
the charity wallet.
● The total FETA on holders wallets is the total supply of FETA minus the burned
amount and the amount in the charity wallet. So this is 333,333,333 - (100,000,000
+ 12,000,000) = 221,333,333. We will call this total held FETA.
● The distribution to 0xFETAONE from this transaction is 27,000 / 3 multiplied by
0xFETAONE’s percentage of total held FETA. This is 9,000 * (3,000,000 /
221,333,333) = 121.98795199 FETA.
● The burned tokens from this transaction are the distribution amount / 3. So, in this
case we are burning 27,000 / 3 = 9,000 FETA.
● The charity tokens from this transaction are the distribution amount / 3. So, in this
case we are sending 27,000 / 3 = 9,000 FETA to the charity address.
● Other FETA holders receive a total of 8,878.01204801 FETA, distributed to their
wallets based on their percentage of total held FETA.
