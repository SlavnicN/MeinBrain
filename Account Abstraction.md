2022/10/17 18:13:37
Tags:

# Account Abstraction

- want to resolve the issue of one address for all, with a high risk if you loose your private key
=> AA would bring a more customizable account with a better management if credential are lost (?)
- key concept of Eth and in the core of EVM is that the Account (the object that hold the token) and
signer (the object that authorize to move those token) are the same object.  
=> Solution is to decouple those 2 objects buy making the account object a smartcontract
-> each user deploy a smartcontract that correspond to there account, with specific setting to there need
!= from SmartContract wallet 
    -> its a SC living on chain still managed by a native EOA

- The signature scheme and eliptic curve are hardcoded in the EVM. (maybe find a better place for this note)

#question:  Smart contract wallets on L1 must use various tricks and build custom infrastructure to emulate AA properly. For example, you need to use off-chain servers, called relayers, to subsidize the transaction fees required to execute transactions on a smart contract wallet.


- AA will allow to have only SmartContract account, no more EOA. And it will also bring:
-> Multicall: do batches of tx in one atomic tx
-> Session key: 
    - Give a limited acces to some Dapp to your token instead of "all or nothing". 
    - And also has the possibilty to recover key (#question: so we need a KYC), by replacing the private 
        key that own the smartcontract AA 
    - no seed phrase needed 
-> Multi-factor auth and security enhance
    - several factor auth
    - list of scam address to auto block Tx to 
    - daily transfer limit (gnosis have it)
    - integrate off-chain security services (check integrate of nft on opensea)
    - auto tx inspection and check 
-> Plug in:
    - Can tailor(add/remove feature) the account to your need (gaming, social recorvery, session key)
    - help keep the account up to date in terms of feature that will come in the future 
-> Pay gas fee in other token (#question how? dig deeper this subject)
-> Can replace gas station 
-> Chose different signing scheme
    - #question So what it's the smart contract that implement the new signature and verification ? And
        also the wallet on the other hand has to imp it? Not sure how this work since the signature is part
        of the protocol ?
    - can use security of iOs and Android as hardwallet (enclave)
    - Quantum safe algo
    - more gas efficient algo 
-> SC upgradibilty on the AA SC (this is already availibal on gnosis )

The goal of AA is to have a lot of what offer gnosis natively on chain, that's why L2 are a good solution

validate = verify that the tx is valide and that it will be paid
- For instance, the validation on ethereum is done by the EVM, it has to verify the signature, the nonce, 
    that you have enough gas ... (all of that is approx 21k gas)
-> on AA you can program what you want the verification to be 
-> with AA you can also verify off chain signature 
-> verify signature done off chain (not sure I understood this: the only object that can verify off chain 
    signature is the wallet ? ) This is manage by eth eip and wallet like metamask implement that, here 
    it will be native to the AA smartcontract (I don't see how this is different than what we have )

As a dev you have to think of: 
-> AA are smart contract and need to be deployed (take that into account for the work flow)
-> the address of the account will be computed like a smartcontract(not derive from a signer )
-> you can multisig
-> off-chain signature are validate on-chain (no use of ecrecover(m,sign) but methode in the AA SC)
-> multi calls

-> Session key principe is very cool, you can bind a key used by a Dapp or service with several policies
    for instance timestamp of use, which methode can be used by this key etc. So that you won't need to 
    approve/confirme everytime you have a transaction to make. Everytink will be automatically executed 
    


## New article 

- Use smartcontract wallets instead of EOA
- Real Acount Abstraction need modification in the consensus layer of Eth, but
    not EIP 4337

[[EIP 4337]]

    
---
# References

https://www.argent.xyz/blog/wtf-is-account-abstraction/
https://www.argent.xyz/blog/part-2-wtf-is-account-abstraction/
https://www.argent.xyz/blog/part-3-wtf-is-account-abstraction/