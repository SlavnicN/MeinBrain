2022/10/05
Tags: [[blockchain]] [[Solidity]] [[security]]
# How to Audit a Smart contract

First check to do: 
- run slither (will not catch everything but can help for start)
- Manuel review

Common vulnerability to check:
- [[Retreance Attack]]
- [[Oracle Manipulation]]
- [[bad randomness]]:
- [[Denial of Service]]:
- [[forced ether reception]]
- [[incorect interface]]
- [[over-underflow]]
- [[Race Condition]]
- [[unchecked external call]]
- [[unprotected function]]



# References 
- https://github.com/PatrickAlphaC/hardhat-security-fcc/
- https://twitter.com/tinchoabbate/status/1400170232904400897
- https://learn.openzeppelin.com/security-audits/readiness-guide
- For Oracle manipulation exemple: 
    https://github.com/PatrickAlphaC/hardhat-security-fcc/blob/main/contracts/LiquidityPoolAsOracle.sol