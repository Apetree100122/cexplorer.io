# Developers Hello developers! Below are the data and outputs
we have prepared for you. Please avoid scraping html outputs 
on website without written permission. 
Thank you for respecting this. ## Instances
We are supporting various enviroments https://github.com/cexplorer/cexplorer.io/blob/main/doc/instances.md
## Permalinks   blocks https://cexplorer.io/block/%blockHash% 
epochs https://cexplorer.io/epoch/%id% 
transaction https://cexplorer.io/tx/%txHash% pool https://cexplorer.io/pool/%poolId% asset https://cexplorer.io/asset/%fingerprint% policy https://cexplorer.io/policy/%policyHash% address https://cexplorer.io/address/%addr% Stake key https://cexplorer.io/stake/%stakeKey% script https://cexplorer.io/script/%scriptHash% datum https://cexplorer.io/datum/%datumHash% ## Static snapshots
from our API We are refreshing snapshots every 3 hours. 
There are no limitations on querying (FUP)
Basics
```
 global - https://js.cexplorer.io/api-static/basic/global.json

``` Pools  list - https://js.cexplorer.io/api-static/pool/list.json hex2bech - https://js.cexplorer.io/api-static/pool/hex2bech.json detail - https://js.cexplorer.io/api-static/pool/%poolIdBech%.json banned - https://js.cexplorer.io/api-static/pool/banned.json  
Assets  detail - https://js.cexplorer.io/api-static/asset/detail/%fingerprint%.json
DeFi  list (TOP) - https://js.cexplorer.io/api-static/defi/list.json    
## Live API this year
```
