
# Week 10 - 14 oct

-- High

- Casion POC
    - [X] Write TBR spec/doc for Casino jira tickets
    - [X] Read the SVP Casino
    - [ ] (maybe) Create interface with the const for Roles and for data struct
    - [ ] Add CI to gitlab branch dev_casino 
    - [ ] Add reentrancy protection and do a checkup with the list
    - [ ] Add check isContract()
      ->  maybe we don't need it since the only contract address is used 
          during deployment 
    - [ ] Add smock test
    - [ ] try test with foundry 

- AAVE fork:
    - [X] Understant why deploy doesn't work 
        -> the TX were stuck in pending because the gas paid was too low to 
            be processed 

- HR - Administratif 
    - [ ] Change mail xdev to Eniblock
    - [ ] Change LinkedIn
    - [ ] Prepare Welcom to the Jungle itw
        - [ ] First version 
        - [ ] Train with people 
    - [X] Github Eniblock account 
    - [X] Resume update for Eniblock

- Skill rampup
    - [ ] Play with Ethernaut
      - [X] Add Wallet on Slack
      - [ ] 1. Fallback
      - [X] Recovery (web3 team workshop) 

- Web3 team workshop
    - [ ] require vs import in .js 
    - [ ] how to see if hh node is on the fork 
    - [ ] how to find the block number when a SC was deployed 
    - [ ] Can't access to the contract via the fork, use the hardhat console ? 

-- Medium

- [ ] Play with tenderly
- [ ] Play with snapshot HH
- [ ] Update Swap SC HTCL, Security
- [ ] Add terminal Solidity
- [ ] Account Infura
- [ ] How to dev eth wallet
- [ ] Try Rust Dev Node
- [ ] Check Rust in BC (<https://ink.substrate.io/>)
- [ ] Search for top 10 security breach on Tezos SC
- [ ] Do same work done on working group for eth

# Week 25 - 30 sept

-- High

- Casion POC
  - [X] Reorginse discribe and it test
  - [X] Replace requires with error solidity, better gas usage
  - [X] GetInfo change to return srtuct instead of list of returns var
  - [X] Clean format

- AAVE fork:
    - [X] Understant why deploy doesn't work 
        -> the TX were stuck in pending because the gas paid was too low to 
            be processed 

- [X] Audit exercise TheSandbox  
    - [X] List basic vulnerability to check
    - [X] Understand the smartcontract
    - [X] Review done 

# Week 05 -> 09 Sept

-- Meetings

-- High

- Casion POC
  - [X] Meeting with Maxime
  - [X] Write some test
  - [X] Write event
    - [X] Test event
  - [X] do a table to explain the roles
  - [X] Test coverage
  - [X] Track gas consumtion
  - [X] Change MANGER_ROLE to MANAGER_INV_ROLE and replace them by owner for functional usage
      Manager role is for a real persone, it's more for calculate the dividend etc
  - [X] Add whitelist/blacklist role instead of using only Investor role for that(investor role
      doesn't have any functional interest in the smart contract)
      By default you should be blacklist while you are whitlisted by the entrypoint
  - [X] No need for ownable put multisig as DEFAULT ROLE

- [X] Pull request for Pytezos


# Week 29 -> 2 August
-- High
- Casion token
    - [X] Keep same entry point for multisig 

# Week 22 -> 26 August
-- Meetings
- [x] Eniblock weekly
- [x] Sprint review plannig

-- High
- [x] Prez Lazy Mint Gas Station
    
# Week 15 -> 19 August
-- Meetings
- [x] Eniblock weekly

-- High
- [x] add pytest cmd workflow into clk 

# Week 08 -> 12 August
-- Meetings
- [x] Eniblock weekly

-- High
- [x] Create a confluence/mira page for lazymint, gas station ... 
- [x] Set meeting with Maxime, Kei, Ahmed and Alex for lazy minting and gas station 
- [x] Read and understand lazy mint 

# Week 01 -> 05 August
-- Meetings
- [x] Xdev weekly
- [x] ITW
- [x] Prez to Sam what have been done 
- [x] Sprint review
- [x] Sprint planning

-- High
- [x] Prepare question for interview

# Week 25 -> 28 July
- [X] write pytezos test integration 
    - [X] full nominal scenario
    - [X] deploy and run on testnet via Flexteza (through clk) 
- [ ] Play with Ethernaut \
	- [X] 0. Hello world
# Week 30 -> 3 May/June
-- High
- [X] List of ticket for Skynet

# Week 6 -> 10 June

-- High
- [X] Confluence page on Spike eth 
- [X] Ask for feedback at the end of the prezh (see Meeting.md Gaetan meeting)

# Week 13 -> 17 June
-- Meetings
- [X] Spike ETH
- [X] Magic estimation
- [X] Intro to Gherkin
- [X] Weekly blockchain 

-- High
- [X] Move confluence page for spike in Wallet
- [ ] write pytezos test integration 
    - [X] simple create() call to the SC with pytezos
    - [X] try to run it on local node


# Week 20 -> 24 June
-- Meetings
- [X] Sync meeting for demo
- [X] Xdev weekly
- [X] Demo Framing 
- [X] Quality retrospective
- [X] Quality point goals
- [X] Weekly BC

-- High
- [X] Prep prez on Forge/Seaport
- [] write pytezos test integration 
    - [X] unittest on create ()
- [X] Write page confluence to show differences between Taqueria/pytezos


# Week 27 -> 1 June/July
-- Meetings
- [X] Meeting with Maxime
- [X] Xdev weekly
- [X] Xdev Monthly
- [X] Meeting Taqueria vs Pytezos
- [X] Mob programing Pytezos

-- High
- [X] Modify name of tickets
- [X] Do a meeting with different people that used Taqueria/Pytezos/SmartPy to weith the pro/con

# Week 04 -> 08 June
-- Meetings
- [x] Mob programing Pytezos
