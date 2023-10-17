2023-10-13
Tags: [[Tezos]] [[Octez]]

# Octez client

Run the client:
octez-client --endpoint https://ghostnet.ecadinfra.com config update

Disable warning:
export TEZOS_CLIENT_UNSAFE_DISABLE_DISCLAIMER=yes

Gen keys:
octez-client gen keys alice

Show keys:
octez-client show address alice

Faucet:
https://faucet.ghostnet.teztnets.xyz/

Get balance:
octez-client get balance for alice

Block explorer:
https://tzkt.io/
https://better-call.dev/

Create aliases:
octez-client remember contract bob [address of contract]

Send tx:
octez-client --wait none transfer 5 from alice to bob

Call contract:
octez-client --wait none transfer 5 from alice to contract1 --args '5'
    - [*] carfull for param, a string param is past: '"hello"'
            and no accent.
    - [*] need to put the limit burn ' --burn-cap 0.1', number max of 
            token you allow to be burned, 

k
---
# References
