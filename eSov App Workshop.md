2023/01/23 11:04:08
Tags: [[eSov]]

# Idea

Avalanche: The validator can't be the user on phone, need server/node of some
sort.
# Crypto workshop
- 
# eSov App Workshop

- Keep the payment of the app at install 
- il veux pas lie un wallet eSov avec une ID. Key activation not linked to the 
    wallet
- il prefere faire tout d'une seul traite 
- Il veut des images video dans le futur 

- notion de Stacking et de Opt-in Opt-out sont pas lie 
- stacking = tout les token EZR que tu as joue sur la remuneration final. pas 
    de notion de blockage de token/ ezr stack ou pas stack
- L'utilisateur est oblige d'avoir des EZR sur sont wallet sinon il paye le double
    pour pouvoir faire la recorvery 
- simplifier le stacking reward dans un premiere temps pour pas trop complexifie les choses.
- Modifier sur le pourcentage de stacking en fonction d'un modifier. 
(eg 120% de 20% pour les agent opt-in)
- Test peuvent etre lance pendant une recorvery et en dehors des recorvery (=
    comment et qui initie le lancement de ces test en dehors des recorvery)
    un truc aleatoir de date genre en back(donc centralisation) 
    Comment genere le calendrier des tests de facon decentraliser

[?] what if the validator is not responding 

# Presentation

    - Approfondir MPC
    - Sur ce qu'on sait faire, ce qu'on pense pouvoir faire, ce qu'on peut pas 
        faire => Sur toute les solutions, un tableau pour montrer les pistes.
    - Reprendre les notes d'Amal
    - Simplifier la strat de Nassime, rendre le diagramme de sequence plus ludique
    - Plus de detail sur les Homomorphisme

# Sprint2 presentation a Fred

    - Appel ID/Android peut cree qu'un seul compte par exemple
    - 1 Payement = 1 Account
    - On garde la gas station, l'utilisateur ne doit pas gere de Matic pour la 
        MVP1
    - Regarder l'account Abstract pour la suite pour pouvoir gere les payement 
        en token ezr
    - (Nassime) Pourquoi tu dois ajouter des matic si on a une GSN ? 
    - Gere un Address book
    - Bundle is a mint process, not transfer (sushi swap, quick swap), once pre
        Account. Limited offer 2 mounth
    - Menu deroulant pour les exchange (ajouter dans l'app)
    - (Nassime) c'est quoi ce claim 0.05 random deja ? 
    - Pour la connection Panel Admin, connection metamask or login mdp (with 2FA)
        Control des tokenomics. Securise la connection pour avec Oauth
        Avoir un Super Admin et Admin (super admin can add or delete admin)
        Voir avec nassime pourquoi besoin du wallet, on peut tourner autour de ca
        Backoffice, en ligne, c'est pas une app mobile
        C'est la tresorie yousove qui paye tout ces changement
    - Implement multi-sig down the road

# Meeting Frederic prez solution

- whitebox cryptography (see with cryptoExpert) 
- RSA 
- create a seed in a WBC 
- use ZKP to verify the uniquness of the seed
- cypher question in WBC
- Key managment/public data BC

=> Not much, it was just the presenation for incorporating WBC


---
# References
