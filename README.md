# HCP-Conenctivity



Pipeline.ipynb

Scaling Parameters to be defined:

> ```
> scaling_params
>     "apply_log" : boolean # whether
>     "beta" : float # exponent applied on connection strength
>     "coverage" : string # ["whole", "left", "right"]
>     "weigh_topo" : boolean # whether apply log to connection strength
>     "scales_known" : list of int # scales chosen to be the known network
>     "scales_toPredict" : list of int # scales chosen to be the network to predict
>     "isAverage": boolean # whether the output dataset is average data
>     "isGraph": boolean # whether the output dataset is an adjacency matrix
> ```