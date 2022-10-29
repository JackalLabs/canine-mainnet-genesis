# Proposal #1  Jackal Storage Upgrade

This is a proposal to do a software upgrade to the v1.2.0 software tag of the Jackal Canine-Chain codebase on block height 118040, which is estimated to occur Friday November 4th, UTC 13:00. Block times have high variance, so please monitor the chain for more precise time estimates.  This upgrade would be consensus breaking.

## Features:
This upgrade includes a push to enable storage providers earning block rewards & verifying storage deals.

It also bumps the Cosmos SDK version from v0.45.9 -> v0.45.10, Tendermint from v0.34.21 -> v0.34.22 as well as  IBC from v3.3.0 -> v3.3.1

## Preparing for the Upgrade
If using cosmovisor, manually build & copy the canined binary.
 
Otherwise wait for your node to halt at the upgrade height, then install and run the v1.2.0 binary. 

## Disclaimers

The upgrade is anticipated to take approx 30 minutes, during which time, there will not be any on-chain activity on the network. 
 
In the event of an issue at upgrade time, we should coordinate via the validators channel in discord to come to a quick emergency consensus and mitigate any further issues.