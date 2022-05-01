# GraphQL-Uniswap
Downloaded data from GraphQL and plotted variables

Got data from Unisqap matic GraphQL using requests 
Converted the json output into csv and dataframe

 Plotted the following across time(atleast last 3 months  - group by averages for a day) for fee tier 0.05%:
    1. Liquidity
    2. volumeUSD
    3. VolumeToken0
    4. VolumeToken1
    5. FeesUSD/Liquidity
    6. FeesUSD/volumeUSD
    
    Many values were zero, hence in FeesUSD/Liquidity and FeesUSD/volumeUSD many data was NaN(0/0-indeterminant).
    So I replaced all NaN values by 0 and did the plotting.
