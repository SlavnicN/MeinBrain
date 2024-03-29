# Week 24 - 28 Juillet 
- [ ] Repair backend for the aws page
- [x] Slides Swisslife smartcontract
- [ ] Terraform deployement S3 of Yousov

# Week 05 - 09 Mai

Article Metadev3: 
- [ ] Write 2 articles on blockchain 
eSov
    Other tickets:
	- [ ] Write down task remaining 
    Audit:
        - check other tools from: https://consensys.github.io/smart-contract-best-practices/security-tools/static-and-dynamic-analysis/
        - [ ] Verify that the app is working with change with tx.origin
            - why does the forwarder do not have this probleme
        - [ ] Add require where needed 
    Doc:
        - [ ] writer documentation/archi of yousov app
            - [ ] Archi application
            - [ ] Archi smartcontract

Club Metadev3
    - [ ] Estimation whole project
    - [WIP] Define what does the backend here
    - [ ] Look for Diamond NFT
        - [ ] dynamic NFT
    - [WIP] Archi in miro
    - [ ] Restrict page access
    - [ ] how to notify user on nft progress
    - [ ] Do we need a load Balancer for the request from frontend
    - [ ] Look for example of Token fidelity project
    - [ ] Verify that the data now are added in database when minted
    - [ ] Modify name Avatar to Profil or smth like that 
    - [ ] Remove docker on the root file 
    - [ ] Send screenshot of the site to the ux team

Perso
    - [ ] Look for building your own Magiclink wallet with aws Cognito
    - [ ] reconfigure neovim
        - [ ] try to configure nvchad with zero-lsp
    - [ ] Install zsh
    - [ ] fix icons issue in kitty
    

# Week 23 - 26 Mai
Settlemint
    - [ ] Read about STO/ICO/Tokenized Eniblock

eSov
    Audit:
        - check other tools from: https://consensys.github.io/smart-contract-best-practices/security-tools/static-and-dynamic-analysis/
        - [ ] Verify that the app is working with change with tx.origin
            - why does the forwarder do not have this probleme
        - [ ] Add require where needed 
    Doc:
        - [ ] writer documentation/archi of yousov app
            - [ ] Archi application
            - [ ] Archi smartcontract

Club Metadev3
    - [ ] Estimation whole project
    - [WIP] Define what does the backend here
    - [ ] Look for Diamond NFT
        - [ ] dynamic NFT
    - [WIP] Archi in miro
    - [ ] Restrict page access
    - [ ] how to notify user on nft progress
    - [ ] Do we need a load Balancer for the request from frontend
    - [ ] Look for example of Token fidelity project
    - [ ] Verify that the data now are added in database when minted
    - [ ] Modify name Avatar to Profil or smth like that 

Perso
    - [ ] Look for building your own Magiclink wallet with aws Cognito
    - [ ] reconfigure neovim
        - [ ] try to configure nvchad with zero-lsp
    - [ ] Install zsh
    - [ ] fix icons issue in kitty
    
# Week 15 - 17 Mai
Settlemint
    - [ ] Read about STO/ICO/Tokenized Eniblock

eSov
    Audit:
        - check other tools from: https://consensys.github.io/smart-contract-best-practices/security-tools/static-and-dynamic-analysis/
        - [ ] Verify that the app is working with change with tx.origin
            - why does the forwarder do not have this probleme
    Doc:
        - [ ] writer documentation/archi of yousov app
            - [ ] Archi application
            - [ ] Archi smartcontract

Club Metadev3
    - [WIP] Define what does the backend here
    - [X] Add Admin page 
    - [ ] Look for Diamond NFT
        - [ ] dynamic NFT
    - [WIP] Archi in miro
    - [ ] Restrict page access
    - [ ] how to notify user on nft progress
    - [ ] Do we need a load Balancer for the request from frontend
    - [ ] Look for example of Token fidelity project

Perso
    - [ ] Look for building your own Magiclink wallet with aws Cognito
    - [ ] reconfigure neovim
        - [ ] try to configure nvchad with zero-lsp
    - [ ] Install zsh
    - [ ] fix icons issue in kitty

# Week 2 - 5 Mai
eSov
    Audit:
        - check other tools from: https://consensys.github.io/smart-contract-best-practices/security-tools/static-and-dynamic-analysis/
        - Tool to check security (trail by bits)
            - [X] slither
                - 1 Reentrency attack solved on claimFreeEZR
            - [-] Mythril
                -> Coudln't make it work

        - [X] Change tx.origin (can be dangerous if a admin use wallet else
            where than ESOV, the smartcontract could fallback to esov and 
            do stuff)

        - [X] In file RecoveryFactory, replace external from
            getLegalSelectableAgents() to internal
            - [X] was replace to a public

        - [X] Find how not to have issue when compile/deploying smartcontract
            with hardhat

        - [X] check storage write variable and require juste before to see who can
            modify those variable
            => No Issue there
        - [X] Change version to a fix solidity version


Club Metadev3
    - [X] Go through the tickets and precise them
    - [X] Add dashboard in Jira

Avalanche project:
    - [X] Research on Avalanche Subnet

Perso
    - [X] fix clipboard probleme between VScode and rest


# Week 24 - 28 Mars
    Settlemint
        - [X] Prepare slides for references

    eSov
        Crypto
            - [X] Detailed diagram for Mine Researcher
            - [X] Crypto doc
                - [X] Write explaination 
                - [X] Find better variable
                - [X] Add more conclusion to the doc

    Club Metadev3
        - [X] Difference between Vue.js and Next.js as frontend
        - [X] Difference between Next.js and Nest.js as a backend
        - [X] Create the repo on gitlab

    Workflow GitFlow
        - [X] Think of the best practice for Spring/Git etc 
        - [X] Write up good code good practice

    Payinnov
        - [X] Time estimation 
            - [X] Prepare question for better timing => Wait for there responses

# Week 17 - 21 Mars
    Settlemint
        - [X] Read the presentation

    eSov
        App:

        Crypto
            - [ ] Crypto doc
                - [X] Schema 

    Share & Learn
            - [X] Presentation of Scaffold-eth and Tendrely

    Club Metadev3
        - [X] Go deeper in the tickets to precise them

    Workflow GitFlow
        - [X] set up CI on Pull request
            - [X] Make the CI work for my branch
    
    Tezos
        - [X]  Add video links to a file in google drive

# Week 03 - 07 Mars
    eSov
        App:
            - [X] Add test Foundry per smartcontract

    Workflow GitFlow
        - [ ] Think of the best practice for Spring/Git etc 
            - [X] Finish the example for the team

    Tezos Fondation
        - [X] Formation Tezos

    Perso
        - [X] Ligature in kitty

# Week 27 - 31 Mars

    eSov
        - [X] Review code 
            - [X] Ticket
        - [X] Verify Secure Storage of Flutter 
        - [X] Create new tickets

        Crypto
            - [X] Draft presentation to the team 
            - [X] Presentation to client

    Travel Prime
        - [X] Estimation Creation SmartContract NFT: 1 week

    Panelys
        - [X] Workshop, understand their need 
        
    Tezos Fondation
        - [X] Wait for the response
        - [X] Set up formation 
        
    Perso
        - [X] Install kitty and configure it
        - [X] Starship prompt shell 
        - [X] Setup ligature in VSCode (change font)

# Week 20 - 25 Mars

    eSov
        - [ ] Review code 
            - [ ] Ticket
            - [ ] Password send in clear to the smartcontract (hash it with salt) 
        - [ ] Verify Secure Storage of Flutter 
        - [ ] Add test Foundry per smartcontract
        - [ ] Create new tickets

        Crypto
            - [X] Continue searching for ZKP
            - [X] Prez sur Account abstraction
            - [X] Prez Stealth Address
            - [ ] Draft presentation to the team 
    
    Workflow GitFlow
        - [ ] Think of the best practice for Spring/Git etc 
            - [X]  Miro brainstorm 
            - [X] Prez to the team
            - [ ] set up CI on Pull request
            - [ ] Finish the example for the team

    Travel Prime
        - [X] Prep the meeting 
        - [X] Estimation Creation SmartContract NFT: 1 week

    Payinnov
        - [ ] Time estimation 
            - [ ] Prepare question for better timing => Wait for there responses

    Panelys
        - [ ] Workshop, understand their need 
        
    Tezos Fondation
        - [X] See about the there Learning Course
        - [ ] Wait for the response
        
    Perso
        - [ ] Install kitty and configure it
        - [ ] Install zsh 
        - [ ] Starship prompt shell 
        - [ ] Setup ligature in VSCode (change font)


# Week 8 - 10 Mars

    eSov
        - [X] Ask new about the Auto/Physical recovery 
        - [ ] Review code 
            - [ ] Ticket
            - [ ] Password send in clear to the smartcontract (hash it with salt) 
        - [X] Code screens (ticket associated)
        - [ ] Crypto: Prez sur Account abstraction
        - [ ] Think of the best practice for Spring/Git etc 
            - [ ]  

    Payinnov
        - [X] Prepare question for the Tezos integration
        - [X] Ask quesiton to Tezos Fondation
        - [ ] Time estimation 
            - [X] See with Faisal
            - [ ] Prepare question for better timing 

    Panelys
        - [ ] Workshop, understand their need 
        
    Tezos Fondation
        - [ ] See about the there Learning Course
        
    Perso
        - [ ] Install kitty and configure it
        - [ ] Install zsh 
        - [ ] Starship prompt shell 
        - [ ] Setup ligature in VSCode 
# Week 6 - 7 fev
-- high
    NFT horses project:
        - [X] review with Faisal 
        - [X] Meeting with client
        - [X] compte rendu avec Constant

    Carbonds
        - [X] Meeting with client
        - [X] Compte rendu Amal

    eSov
        - [ ] Redaction du backlog
            - [ ] Review the thing Nassim put in Jira 

        - [ ] Copy the compilation generation on Scaffold-eth 
        - [ ] Think of the architecture 
            - [X] put on paper the current archi
            - [X] Write different workflow
        - [X] Send the compte rendu Crypto
        - [X] Check repo
        

    Prez Learn:
        - [ ] Tendrely
        - [ ] Slither, how to configure it 

    - [ ] Start learning Go
    - [ ] Defi project  
        - [ ] Read TP on defy
        - [ ] Review Lionel TP

-- low
    - [ ] Add dev Metamask on Chrome
    - [ ] Add filter to metadev3 mail
    - [ ] Maybe see the treesitter probleme in neovim

# Week 30 - 03 jan/fev
-- high
    NFT horses project:
        - [X] see with Constant 

    eSov
        - [X] Prepare prez on blockchain public/private
        - [X] Write  and send the compte rendu
        
        - [X] think about question triggering more the problematic not the 
            solution 
            - [X] Put on the miro everything we saw during the workshop crypto

        
        - [X] Search for the notification/handler decentralized and secure 
            - Need to test some of theme (Lambda, EvenBridge )
            - Firebase with privacy token
            
    Panelys
        - [X] suggest a blockchain archi (Push+Cacao) (6 Fev)
            - Doc + onboarding client

    Prez Learn:
        - [X] Foundry and Forge
        - [X] Custom error

-- low
    - [X] Configure airpod on ubuntu
        - https://askubuntu.com/questions/922860/pairing-apple-airpods-as-headset

# Week 23 - 27 oct

-- high
    Settlemint
        - [X] try out there solution 
            - [X] watch tuto video in the mail
            - [X] (maybe no need) prepare small project to play with
            - [X] meeting with guys from Settlemint

    eSov
        - [X] Repartition des taches
            - [X] Split between Joe, Lionel, Francois, Thomas

        - [X] Mise en place de l'env de dev 
            -   [X] Wait to see with Fred
            - 

        - [X] Search for the notification/handler decentralized and secure 
            - Need to test some of theme 
            - [ ] Lambda, EvenBridge 
        - [X] Benchmark on protocol crypto 
            - Thomas and Nassim on it 
            
    Panelys
        - [X] Read docs again before meeting monday 

    - [X] Add navigo
    - [X] Config Zulip
            
    R&D
        - Find idea that solve a specific probleme
            - DEFI AI ? 
            - Find SC in general in on-chain 

# Week 16 - 20 oct
-- Onboarding Metadev3 
    -- high
        eSov
            - [X] Read eSov docs
            - [X] Prepare questions for Crypto Workshop 
            - [X] Review questions with on eSov with Nassime
            - [X] Prep workshop fonctionnelle
        Panelys
            - [X] Read Panelys docs
            - [X] Brainstorm archi blockchain

        - [X] Redo CV with Go and Metadev3 lines 
        - [X] Check mutuel with Valentina 
    -- low
        - [X] Add picture in slack
        - [X] Deactivate bios pwd
        - [X] Download slack
        - [X] Config neovim 
        - [X] Configure neovim in vscode 
