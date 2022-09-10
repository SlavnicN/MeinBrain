2022-08-30
Tags: [[SmartContract Upgrade]]

# SmartContract Upgrade Alternative
- Hardcoded value in the SC that would change the behavour of the code 
    when set to specific values (like compile definition var)

- Have a central smartcontract register that save the address of the 
    SC to call, so that you can just modify this registery to point to
    point to a new contract. But doesn't keep the storage.

- Strategy Pattern
- Pluggable Module


=> All of those require that the core are bug free and won't need any
modification

---
# References
