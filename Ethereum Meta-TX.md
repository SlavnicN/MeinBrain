202208051422
Status: #idea
Tags: [[Lazy minting]] [[mint]] [[blockchain]] [[Ethereum]]

# Ethereum Meta-TX

- transaction that englobe the signed TX is send to a "Forward smart contract"
- in case of erc-20 transfer problematique of the approuve/transfere from come here. Because we need to give to the forward smartcontract approval to use our token -> the approve() cost gas
=> Solution: extend the erc-20 with the function permit() that change the allowance token by using a sign msg and not through a TX (EIP-2612)

? -  Not sure I understand the graph in the artical, why do we need to 2 sign message (permit() and transferFrom() )

- There is a EIP for Meta-TX Forwarder contract

Problematics:

- what about wanting that a smart contract signe the transaction and not the EOA ?
- what about Multi-sign wallet that hold the user token? how to make the sender of the transaction do a Meta-Tx
=> Solution: [[EIP-1271]] which allow for a contract to verify a signature on behalf of another smartcontract

---

# References

<https://betterprogramming.pub/ethereum-erc-20-meta-transactions-4cacbb3630ee>
<https://eips.ethereum.org/EIPS/eip-2612>
<https://eips.ethereum.org/EIPS/eip-2770>
<https://eips.ethereum.org/EIPS/eip-2771> (contract interface for receiving meta TX through trusted forwarder)
<https://soliditydeveloper.com/meta-transactions>
