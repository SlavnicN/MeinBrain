2022-09-05
Tags:

# Casion POC FAQ
- [ ] verify gas consomation with multi heritage of the same class (https://miro.com/app/board/uXjVOUCqDo0=/?moveToWidget=3458764532162680571&cot=14)
- [ ] Role is in Multisig ? 
- [ ] Check solmate instead of openZepplin for ERC20
- [ ] Demande a Maxime, Do we do everything from scratch for proxy or use Hardhat 
    pluggin ? 
- [ ] how many tx can be sent at once ? On tezos it's only 5 tx
- [ ] What is the use case of a Payble Token (ERC1363)? Do we need it here ?:
- [ ] The multisig doesn't sign ? It just add a hasVoted value that it will check ? -> Do we do the same on Casino ? 
- [ ] Do we need the function Signature of the proxy or Token ? 
- [ ] we need to do a signature of signature ? 
- [ ] Create an instance of Token in Multisig ? 
- [ ] How to instanciete the token if we have a proxy in between
        -> We use the interface of Token + the address of the proxy ?
- [ ] How to block function that we have herited but don't want to use in our Token
- [ ] Do we trust in https://github.com/odyslam/foundry-upgrades/blob/main/src/test/ProxyTester.t.sol

- Contract mutlisig tezos
    - [ ]  what is the strg in contract object 

- [ ] Why Enumarble over classical AccessControle (Frederic) 
---
# References
