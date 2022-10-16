2022/10/10 15:21:44
Tags: [[Casino]] [[Blockchain]] [[Defi]]

# Meeting Arturo - Alexandre

- Problem de liquidation cote Defi 
- liens entre les whitelist tokenize et ceux qui peuvent liquider sur le protocole AAVE 
- Quand tu liquide une personne sur AAVE tu vas repayer ca debt 
    - tu recupere son depot (le cToken)
    - et tu rembourse en stable coin un partie 

- qu'est ce que represent le cToken (un bien, groupement de bien ...)
    - SVP = groupement de bien, un mint de ces token fait lors du deployement du contract et qui restera fix 
    - lorsqu'un bien sera ceder, chaque investieur a ce bien recevra un virement bancaire de la valeur de l'investissement
    - le prix du bien changera mais pas le nombre de token 

- Casino Wallet
    - Gnosis ou Eniblock wallet ?
    - Gnosis sera un investiseur visa av is de Tokenize, managment companie 
    - Token wallet = wallet TAG/EAG 
    - (ici on parle de Wallet Casino pas user) pas prevu de faire des token wallet en dehors
        => c'est un wallet technique qui appartient a l'issuer, pas besoin de faire de KYC. C'est just un wallet qui peut recevoir des mint ou des transfere
    - les utilisateurs on pas de wallet EAG/TAG mais des wallet extern(metamask)
    - fonctionalite maske de wakam ?
    Par defaut:
        - Quand un investiseur fait un KYC on fait rien 
        - Mais quand on le whiteliste soit:
            - il a pas de wallet et on lui en cree un dans EAG/TAG
            - il a renseigner un wallet precedement et on l'utilise

    - Token retransfere a Casion

    - Compte issuer and compte investisor et il s'auto kyc avec compte administartor  

    - why mint if we have a limited supply of Casino token ? 
    - we mint to an address, how to transfer token minted to a contract to an address ? 
        - 1 il mint to les token sur l'address de Casino 
        - 2 il feront tout les transfere 

    - Address de Casino = un address que nous on a pas mais que eux il gere
    => virer multisig pour utiliser Gnosis ? 
        Admin du token = address du gnosis safe
    - t'as pas de poids dans Gnosis, (mais personne l'utilise)
    => Gnosis = super admin -> qui passe par le multisig
    ===> Laissez tomber Multisig
    - Owner de CasinoToken est Gnosis Safe, 

- DEFI
    => Decision partir sur AAVE  
        - Remplir ARC pour deployer le token sur le protocol principal de AAVE
        - contract permissionner, whitelist les depositaires 
        - Fork de AAVE = admin c'est Casino
        - Oracle AAVE utilise Chainlink
            => faire notre propre Oracle gere par des gars de Casino/immobilier 
        => Pas le choix de faire fork AAVE, et protocole gerer par Casino.
            - Et ils vont gere le fork et de tout faire sur le mainnet 
    - vue que l'utilisateur donne ces token Casino au contract AAVE il faut whitelister les 
    contract AAVE
    - Visa vi de Tokenize, AAVE c'est un investiseur comme un autre. 
    => Faut concidere les contracts AAVE comme des wallet technique 

    - est ce que les stable coin et le virement fait lors de la cessession d'un bien sont lie ? 

    - Problem lie a l'oracle, beaucoup trop centraliser 
    - Liquidation bot? 
        - parcourir les utilisateur pour savoir si ils sont en periode de liquidation
        -> utiliser un liquidation bot pour avoir l'info, c'est un casino qui approve la
            liquidation
---
# References

