202207051723
Status: #idea
Tags: [[pytezos]] [[tezos]]

# Pytezos from scratch


``` python
@tzc.command()
def pytezos():
    """Run some interactive code using pytezos"""
    from pytezos import ContractInterface, pytezos
    p = pytezos.using(
        shell='http://localhost:18731',
        key="edsk3QoqBuvdamxouPhin7swCvkQNgq4jP5KZPbwWNnwdZpSpJiEbq")
    c1 = ContractInterface.from_file(
        "/home/sam/Prog/xdev/smartcontracts/tezos/fanlive/test/build/NFT_Auction/step_000_cont_0_contract.tz"
    ).using(key=p.key, shell=p.shell)
    o = p.origination(script=c1.script()).send(min_confirmations=1, ttl=110)
    import IPython
    dict_ = globals()
    dict_.update(locals())
    IPython.start_ipython(argv=[], user_ns=dict_)


clk extension install git@gitlab.com:xdev-tech/clk_extension_tezos_client tezos_client
clk tzc sandbox flextesa start
clk tzc sandbox flextesa logs
clk tzc sandbox flextesa start --follow
```

``` python
    p = pytezos.using(
        shell='http://localhost:18731',
        key="edsk3QoqBuvdamxouPhin7swCvkQNgq4jP5KZPbwWNnwdZpSpJiEbq")
```
-> this create an object client that point on the shell node address and with the secret key specified 

``` ad-question 
    why the need of the key ? 
```
``` python
    c1 = ContractInterface.from_file(
        "/home/sam/Prog/xdev/smartcontracts/tezos/fanlive/test/build/NFT_Auction/step_000_cont_0_contract.tz"
    ).using(key=p.key, shell=p.shell)
```
-> create the interface of the smart contract by specifing who is generating it p.key and on which node 
p.shell 

``` python 

    o = p.origination(script=c1.script()).send(min_confirmations=1, ttl=110)
```
-> Deploy smart contract c1 on the client p
-> originate() directly on the smartcontract interface call also origination() but if the client wasn't 
specified during the creation of the interface then we need to specified it in the using() 
-> min_confirmation = num of block injection to wait before returning 
-> ttl = num of block to wait in the mempool before removal 


---
# References