2022-12-12
Tags:

# SSH with multiple account git

Still trying to figure it out I think I got it

'''
#Default account
Host github.com
	HostName github.com
	User git
	IdentityFile ~/.ssh/id_rsa_default

#perso account
Host perso.github.com
	HostName github.com
	User git
	IdentityFile ~/.ssh/id_rsa_perso
'''
    
---
# References
https://gist.github.com/jexchan/2351996
https://www.freecodecamp.org/news/manage-multiple-github-accounts-the-ssh-way-2dadc30ccaca/
