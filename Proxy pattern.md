2022-08-30
Tags:[[SmartContract Upgrade]]

# Proxy pattern

It's a combination of:

-   A proxy SC that delegate the call
-   A Impl SC that has the logic to run

-   the proxy SC has all the storage and keep the msg.sender
    when the Imp SC is called

-   To update the Imp SC, you change the address that the proxy is pointing to
-   Multiple proxy can point to the same Imp SC
-   Carefull about the [[Proxy Storage Clashe]]

---

# References
