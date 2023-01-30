2023/01/20 13:24:59
Tags:

# Settlemint Project

- It's a tenderly like app with less debug feature and more node/clusture
    controle
- You can track the health of each node and send rpc directly to it

Question:

- [X] how are the private key from external wallet managed 
    -> No import account 
    -> "Accessible account": They manage the key
    -> "HSM": Don't manage the key, launch a new service = cost

- [X] Network stat are for the entire BC or juste for the node your are running 
    -> yes 

- [X] Why do you need to specify deployement plan during SC creation 
    -> Each service need to launch a new cluster

- [X] Adding plugging, node, Ipfs, integration add cost each time 
    -> Every new service add a cost to the all app

- [X] What's the value on small project 
    -> No answer yet 

- [X] Dev on the platform directly 
    -> yes but also can integrate with github (not sure with gitlab)

- Integration panel
    -> Interesting but not mandatory

- Forking blockchain, debuggin, simulation
    -> No such thing 
- IDE limitation
    -> One account has access only to one instance of the IDE

Question to ask ourselves:
- Does our client and future client care about 
    - running the nodes 
    - where are they run
- Did we had issue on previous project on RPC (Infura, Alchemy, Moralis... )
- Wallet managment not the best 

=> Too much for what we are doing. 

---
# References

