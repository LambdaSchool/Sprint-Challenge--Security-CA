### I added an SSH key to my github.
##### Steps:
* Created a new ssh key in my Git Bash: ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
* Entered a file in which I saved the key: (/c/Users/you/.ssh/id_rsa)
* Typed a secure passphrase
* Manually started the ssh-agent: eval $(ssh-agent -s)
* Added my SSH private key to the ssh-agent: ssh-add ~/.ssh/id_rsa
* Added this new SSH key to my GitHub account via settings