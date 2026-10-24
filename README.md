# Asset-Allocation-QRT-Challenge
Description:

Each row in the dataset represents a day and an asset allocation, materialized as a portfolio constructed and rebalanced on that day. We give you a history of how that allocation behaved when rebalanced over the past 20 trading days: its daily performance, liquidity behaviour (proxied through weighted volumes), and median turnover.

The goal is to use that historical footprint to predict the sign of the allocation’s performance on the following day.

If the model predicts positive return → trust the allocation.
If the model predicts negative return → short the allocation.