2022-08-30
Tags:[[Proxy pattern]][[Transparent Proxy]]

# Universal upgradeable proxy
- Same as the Transparent proxy but the impl of the update address is also delegated

=> Make it cheaper at deployement and calling
but If the proxy is upgraded to an imp that doesn't have the function to upgrade then the proxy is stuck to that imp

---
# References
- https://blog.openzeppelin.com/the-state-of-smart-contract-upgrades/
