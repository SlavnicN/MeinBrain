2022-12-12
Tags:

# SSH with multiple account git
'''
#activehacker account
Host github.com-activehacker
	HostName github.com
	User git
	IdentityFile ~/.ssh/id_rsa_activehacker

#jexchan account
Host github.com-jexchan
	HostName github.com
	User git
	IdentityFile ~/.ssh/id_rsa_jexchan
'''
    
---
# References
https://gist.github.com/jexchan/2351996
