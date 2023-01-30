2023/01/16 13:42:44
Tags: [[eSov]]

# eSov Project Brainstorm

- Decentralized secret management protocol.

- Main idea: Service to recover password through decentralization service.
    - Network of node that "work" to provide the different shares that will be
        used to recover the password

## Idea

- instead of having a false questions system, it would be better to have 
    a reputation system that is updated for each question distributed. Auto 
    regulated score and no need to send false tx. 

- Instead of question, having your key send to a number of agent and and adjust
    the reputation system by there reactivity 


- ToRead:
    - https://vault12.com/
    - https://tide.org/

## Interogation

- Project in itself:
    - [?] Decentralized code: what does it mean, open source 
        - need more detail (add power point)

- Agent: 
    - [X] how will the agents be awarded
        - EZR thourgh validation.
    - [?] what type of work will they need to do, how will this step be 
            validated

- Blockchain: 
    - [X] On what blockchain, what type of smart contract do we need for that
        - Polygon, see miro for type of smart contract
    - [X] Mobile app writen in Flutter

- availibility: 
    - [X] what about if the user is offline
        - only online 
    - [?] how to notify wallet in the blockchain, chat wallet project
    - [?] what about the web app  

- NFT: 
    - [X] why sending an NFT at enrollement phase
        - Not mandatory point, can be removed
    - [X] why mint NFT for the "chat" 
        - Not mandatory point, can be removed
    - [X] why install a chat module
        - Not mandatory point, can be removed
    - [X] why use nft in a chat module to recover, and what if the tx fails
        the tx is not in the right order
        - Not mandatory point, can be removed
    - [X] During Launch Wallet: who mint and pay the fee for the 1st NTF transfer
        - Not mandatory point, can be removed
    - [X] What does that NFT represent
        - Not mandatory point, can be removed
    - [X] Is there a collection creation with theme.Is it giving early access right
        - NFT collection to give some early acces and discount on EZR

- EZR: 
    - [X] what is the use of EZR token
        - Tokenomic of the protocol
    - [X] why is it so important to have EZR in your wallet to use it
        - It's central to the protocol
    - [X] impossible to transfere EZR outside of the eSov Wallet
        - possible, but tax applied here in ezr
    
    - [?] who will hold the token EZR, the eth that were use to buy those, how 
            to topup it
    - [?] What are the outside means to buy EZR, speculation, utility

    - [X] what is the use case of the voucher, what is the random num inside of it
        - it's more about an Ico than anything else  
    - [X] What is the use of the voucher, buy NFT or Token 
        - it's for token, some sort of lottery


- coinmixing: 
    [?] why coin mixing, is it for the privacy of the Agents
        - in pp for fees too 
        - maybe not necessary 

- security
    [?] how is the DPKI defined
        - ws crypto
    [?] what if someone use the PII of someone else, only public data used here 
    [X] how to avoid error in first entering PII 
        - can modify it in vault
    [X] Airplane mode is kindof sketchy
        - inutile

    [X] what does it mean "the app install the 2nd componenet" 
        - no need, to clanky and maybe even not possible in iOS/Android app     
            store
    [?] What is the link with DPKI and the second wallet
    [?] what is for him a fido complient pwd, lose purpose of the solution by 
        adding a pwd, second Oauth means link to a device
            - in pp 
    [X] Challenges only question, 5-11 is maybe a lot
        - Let's stay with that for now 
    [?] Do you always need the pwd to access the wallet 
    [?] What is a swarm of other elements 
        - ws crypto
    [X] Anybody can recall other wallet with the PII
        - no, we need the questions
    [X] why do the user need to rebuy the app when installing it again 
        - This means if you use another iOS/Android account, you can resync your
            iOS/Android library of app but if you switch iOS/Android account 
            then you need to rebuy it.
    [?] Speak about solution without key, but one is needed for his wallet



- wallet: 
    [X] Who manage the wallet addresses ? Custodial ? Non Custodial
        - Non custodial, the user has controle over it, but app can generate one

    [?] changeing Wallet imply transfering all asset to one wallet to the other
        who is in charge of of the fees once again.
    [?] why use a one time convertor wallet addresse 


- Recovery:
    [X] what are the validation steps for the recovery
        - pii + questions + pwd and need ezr
    [X] Is recovery paid by EZR or other crypto/money
        - by EZR
    [?] what is the cost of a Recorvery 
    [?] How will we identify if the PII is already enrolled or not in the app 
        - com with a smartcontract, mapping 


- Storage:
    [?] How will he access the log of the bockchain
    [?] Will we need a decentralize database  
    [?] Need theGraph to handle the transaction not passed
        - how to handle that in the BC ecosysteme? 
    [?] Does this part need to be decentralized 

- Notification
    [?] iOS could be a problem for receiving notification 
     
---
# References

