### I added an SSH key to my github.
##### Steps:
* Created a new ssh key in my Git Bash: ssh-keygen -t rsa -b 4096 -C "my_email@example.com"
* Entered a file in which I saved the key: (/c/Users/me/.ssh/id_rsa)
* Typed a secure passphrase
* Manually started the ssh-agent: eval $(ssh-agent -s)
* Added my SSH private key to the ssh-agent: ssh-add ~/.ssh/id_rsa
* Added this new SSH key to my GitHub account via settings

P.S. This time I didn't do much because I'm going to buy a new computer where I will set up something like KeePassXC for a password manager. Most of my time I spent on coming up with a well-protected phrase instead of my old passwords. I already use the two factor authentication in some of my applications. Finally, I read several articles about sandboxes and virtual machines.