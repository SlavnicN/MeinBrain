2022/10/13 15:44:44
Tags: [[Gnosis Safe]]

# Presentaiton Safe Core Sdk

Safe Architecture:
    - Contract (Safe, Libraries, Module)
    - Tooling (safe deployement)
    - Services (Tx service, Client Gateway, Notification service, Configuration service)
    - Interfaces (Web, mobile, CLI, SDK)

Safe Core SDK
    -  everything done offchain is handeled by safe-service-client 

![Alt text](img/gnosisSDK.png?raw=true "Title")

1. need to initialize the safe-core-sdk
    - ethAdapter in needed ether lib
    - safeAddress is needed
    - (optional) MasterCopy
    - (optional) contractNetwork, usefull if work on smartcontract not deploy by gnosis

    - txService can used known url or can be hosted by us

2. Deploy a new Safe 
    - Can have a SafeAccountConfig with different property
    - safeDeploymentConfig is set if we want to controle the address where it will be deployed since it's done deterministicly

3. Create a single transaction
3 bis. Create batch transaction
4. Propose a transaction
5. Get a transaction from the service
6. Confrim a Tx
6bis. Reject Tx
7. Execute a transaction

---
# References

