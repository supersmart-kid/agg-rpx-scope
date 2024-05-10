# agg-rpx-scope

## Requirement:

  A dex aggregator on Sei V2 (an EVM compactable chain). 

  As a dex aggregator it should have the following:
  - For selected token A and token B, provide the quote fetching from various dexes
  - enable route to swap picking the best posibile route among the dexes for given pair with liquidity.
  - Should aggregate list of dexes existing on Sei V2 EVM
  - curate dexes interface contract for route exisiting on Sei V2 EVM
  - update the list either by adding more dexes or removing the dexes.
  - backend end server api to manage events and user history