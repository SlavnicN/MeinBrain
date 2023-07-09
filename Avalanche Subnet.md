2023-05-11
Tags: [[Avalanche Blockchain]]

# Avalanche Subnet

Pro:
- Controle over TX fees with native token
- Permissoned blockchain
- Subnet can communicate between each other
- Can be permissoned or not(KYC) 
- Possibility to move from a C-chain to Subnets

Con:
- Validators in subnet need to stake AVAX
- Subnets share storage on disk level, store data into the same database/folder in operating system. no way of chosing where to store that, and 
with whom to share it.
- Validators are not bound to one subnet, it can validate the Primeray network as well as 
different subnet. But Subnets can put restriction on what validator come to it 
- Can be complexe to intigrate with other Subnets if want to communicate 
with them

? how many validators can be set in a subnet
? who chose those validator 


Question for client:
- Does he need interoperability between other subnet in the system 
- If he chose to go Subnets, he need to chose one:
    - EVM
    - Go Rust
    - Custom
    ? Do he really need a Subnet
---
# References
