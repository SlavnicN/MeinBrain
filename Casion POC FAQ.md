2022-09-05
Tags: [[Casino]]

# Casion POC FAQ

- [ ] verify gas consomation with multi heritage of the same class 
    (<https://miro.com/app/board/uXjVOUCqDo0=/?moveToWidget=3458764532162680571&cot=14>)
- [ ] Role is in Multisig ?
- [ ] Check solmate instead of openZepplin for ERC20
- [ ] Demande a Maxime, Do we do everything from scratch for proxy or use Hardhat pluggin ?
- [ ] how many tx can be sent at once ? On tezos it's only 5 tx
- [X] What is the use case of a Payble Token (ERC1363)? Do we need it here ?:
  => this is if we wanted to use that token elsewhere to pay with it, so no need in our usecase
- [X] The multisig doesn't sign ? It just add a hasVoted value that it will check ? -> Do we do the same on Casino ?
  => For now yes

- [ ] Do we need the function Signature of the proxy or Token ?
- [ ] we need to do a signature of signature ?

- [ ] Create an instance of Token in Multisig ?
- [ ] How to instanciete the token if we have a proxy in between
  => We use the interface of Token + the address of the proxy ?
- [ ] How to block function that we have herited but don't want to use in our Token
- [ ] Do we trust in <https://github.com/odyslam/foundry-upgrades/blob/main/src/test/ProxyTester.t.sol>
- [ ] Do we need to set different weight for each proposal
  => Depend on Casino usecase
- [X] Why Enumarble over classical AccessControle (Frederic)
- [ ] Should we increas the liquidity for each transfer ?
  => Depend on Casino usecase

- [ ] why do we overwrite all burn(), beforeTransfere() etc
- [ ] external or public for call done outside ?
- [X] how to get revert error from CasinoToken contract through executTx()
    => Done with the second arg return by call(), see exemple in the smartcontract MultiSigh
- [X] Should we also have ownable
    => Not necessarly, setting a role to the multisig suffice 
- [ ] call external and internal investor instead of manager and investor
- [ ] how to manage the whitlist/blacklist for internal/external manager
- [ ] Do we need transfere from in the multisig
- [ ] Who can pause unpause a contract ? Eniblock or Casino (-> so multisig)
- [ ] Can we mint on an address that is not a user yet ?

- [ ] how to fix openzepplin version solidity to match our contract
- [ ] do we need to add gap[50] at the end of our sc 

Casino specific question: 
- [ ] Should casino make vote available for investor for dividend ?
- [ ] Sould be able to transfer to an address if it doesn't have liquidity balance
- [ ] Should we allow one user to approve transfer from another user
- [ ] Should we allow increase of allowance even if no token availible
- [ ] Should we take into account the liquidityBalance for burn and burnFrom, I don't think so since it's the
    Admin that has that power 
- [ ] Should we increment liquidity for each transfer, or only through the liquidityincrement/decr ? 
- [ ] burnFrom should be in build+sign or only called by superAdmin like transferFrom


Blockchain meeting suggestion:
  - [ ] check difference in time between retunring Struct or direct list data in the
    getData()
  - [ ] cost between getData() and going throug Moralis Indexer

- Contract mutlisig tezos
  - [ ]  what is the strg in contract object

---

# References
