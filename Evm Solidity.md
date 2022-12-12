2022-11-22
Tags: [[Solidity]] [[EVM]]

# Evm Solidity


Abi = interface of your smartcontract that tell to the application how to 
    interact with the SC. Function supported and their args 

TX Contract deployement = the "to" is empty (that's how evm knows it's a 
    contract deployement) and data are the init code 

- EVM is a stack based processor 
    - opcode applyed to stack and add the result back to the stack 
- EVM access and store info from 6 places: 
    - Stack: where the opcode do the work, the stack is volatile 
    - CallData: read only memory from the data field transaction 
    - Memory: tmp storage accessible during the transaction 
    - Storage: persistant
    - Code: code exec and static data storage
    - Logs: write only event output

- file.bin generated during compilation has 2 parts:
    - Init code fragment
    - Code to be deployed

- TX for deployement, the data filed is treaded as code storage and not CallData
    and the init function is not push to the blockchain

- payable keyword does not have an opcode, other function have opcode that 
    verify if it's payable or not (add payable make your smartcontract smaller) 

- storage var does not generate opcode 

- SLOAD on the same slot will cost lest gas. 
    /*
        uint8 y;
        uint8 z;  // Those are on the same slot, so SLOAD on z will cost less
                  // gas than if both were uint256
    */
    
---
# References
https://www.youtube.com/watch?v=RxL_1AfV7N4
