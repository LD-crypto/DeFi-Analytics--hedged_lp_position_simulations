# DeFi Analytics: hedged_lp_position_simulations

DeFi allows for the creation of liquidity pool (LP) positions in a automatic market markers (AMMs). These LP position accrue returns due to swap fees and protocol incentives.

The exposure to the price of the underlying assets can be hedged via borrowing and shorting. To maintain a price neutral position constant rebalancing must be done. This rebalancing locks in losses due to impermanent loss of the LP position and the fees associated with trading and rebalancing.

This repo contains data and notbookes written in python to simulate a rebalancing strategy of an hedged LP position to estimate some statistics on the losses and costs of holding this position.
