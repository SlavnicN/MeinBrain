2022/10/05 19:00:00
Tags: [[How to Audit a Smart contract]]

# Audit Review The Sandbox (staking)

## Idea 

- Replace require by error for better gas management 
- they are some "randomness" in folder raffle, game, catalyst, is there any inheritance here ?
- race condition: the ERC20 approve mitigate by the safeERC20 ? 



## Summary

- 2 pluggin: 
    ContributionCalculator: Use computeContribution (extra share of the reward ?)
    rewardCalculator: manage the rate of the reward
    -> Can mixe those to have different pools


