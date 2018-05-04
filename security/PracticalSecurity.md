# Practical Security

## Steps To Protect Yourself In A Tech World

With the current media frenzy about security flaws and privacy issues in Social Media recently, it's a good time to double check your protection. How secure are you? Do you use a password manager? What about Two Factor Authentication? What about SSH Keypairs or a computer running only open source software?

To the average user, a password manager and Two Factor Authentication will most likely be good enough. But let's be honest. The average user probably also has the mindset of "I don't want to spend my time doing all of that extra work." While they aren't saying it, it's implying that they're security isn't all that important to them. Unless they use very little technology or social media, maybe it's not that important. But the reality is the majority of the population are. So, with that, here are some simple steps the average user can take to better protect themselves from: Identity Theft, Fraud, Extortion, Malware and other smaller, yet still dangerous, situations.

### Set Up a Password Manager

Setting up a password manager is something I have always recommended people to do. It adds an extra layer of security and makes password management a breeze. In today's world, most people have hundreds of different passwords/usernames/accounts they have to remember. This creates a bad case of "use the same thing for everything." This is terrible because it creates a very large base for getting hacked in to/losing control of accounts/becoming a victim of threats.

Password managers take care of this for you. A very popular open source manager is [KeePass](https://keepass.info/). KeePass has a variety of tools to help protect your information, and make it easy to keep track of it all. It can store usernames, passwords and other fields, including notes and files, in an encrypted file. You can then protect that file with a **master password**. It has a password generator to create secure passwords for you, supports Two Factor Authentication and even has a *secure desktop* mode. You can divide your passwords in to groups and identify each group with an icon to make organization easier. It also offers auto-type, auto-type hot keys and drag and drop. These are excellent features for quickly accessing accounts, and don't worry, they're still secure with these features.

To use KeePass, simply go to the [KeePass Download Page](https://keepass.info/download.html) and follow the prompts. After installing, check the box to launch the program. It will open up, and from there you will see an empty page. Simply click "File" at the top left, and create a new form. It will prompt you to store the file in a chosen destination (make sure you don't forget where you store this) and it will ask you to create a Master Password. I recommend making this password a "String" of words with varying upper and lowercase letters, numbers and punctuation marks. You can throw in some symbols too. The key is to make it fairely long (at least 25 characters) to make it more secure and harder to decrypt.

From there you have a couple choices. You can simply select "Ok" to continue, or you can select the check box for "Show expert options." This part isn't necessary, but it does create added security. You can create a Key file, which can be used as part of the master key. It doesn't store any information, so if it were to become compromised, nothing really can happen. However, if you somehow lose the key file, or its contents are changed, you will no longer be able to access the database.

The other option is to add a Windows User Account. It will use data of the current Windows user account to encryption and security. However, if the account is lost, it can't be recovered.

With all options, it is HIGHLY recommended that you create a back up of the files, or risk losing all information. I recommend storing the backups on a separate storage device, such as an external HDD or a thumb drive. (Thumb drives are cheaper and more convenient.) Just, make sure you can not and do not lose the external device, and keep it locked away in a safe place that only you have access to. For the average user, I wouldn't activate a key file or the windows user account. 

There are a ton of options from here, and without deturing from the main topic too much, I highly suggest installing the app and making a dummy setting to play with it and learn how it works. There are also plenty of resources that break down the intracacies of the application to help new users out.

### Two-Factor Authentication

Two-Factor Authentication (2FA) is a type of multi-factor authentication. It utilizes a combination of two different factors: 1) Something they know, 2) Something they have, or 3) Something they are. A good example is paying for something at a store with a credit/debit card. You must provide the correct combination of debit card/pin to allow the transaction to be processed. 

Setting up 2FA on an account is typically a 3 step process. You need to provide your current credentials, even if you're currently logged in. Then, you go to account settings and enable 2FA on your account, which lets the server that manages your login know that you want to enable it. You will be asked what type of authentication you will be using, with the most common being codes sent to your phone by text, call or an authenticor application. Finally, you confirm your change by supplying a token back to the server.

From then on, whenever you want to log in again, you'll enter your username/ID and password as usual, and then be asked to supply the authentication number, whether it was sent by text/call or an application.

The  process for each service that provides 2FA will vary slightly, but this is a general guideline to set it up. Many popular services offer 2FA for customers.
You can find a very comprehensive list of services that provide it [here](https://twofactorauth.org/).

#### For the average user, these two simple steps will suffice. Needless to say, there ARE extra things you can do for added security, should you feel you need it, or you are in a position that requires it.

### GitHub, SSH, GPG and Linux Oh my!

#### GitHub and SSH
Needless to say, GitHub is super popular among developers for projects. It's a farely secure place, but that doesn't mean it can't be broken. To help combat this, GitHub offers [SSH](https://help.github.com/articles/connecting-to-github-with-ssh/) You can use SSH protocol to connect and authenticate to remote servers and services. You can also connect to GitHub without supplying your username and password at each visit. This makes it highly important that you keep your key a secret. You'll want to check for existing SSH keys before generating a new one. After checking, you can generate a key for authentication and add it to the ssh-agent. Then, you can configure your GitHub account to use your new (or existing) SSH key. After setting it up, you can test your connection. 

#### GPG Keys
GPG is free encryption software that's complient with the OpenPGP standard. You can use GPG to encrypt files that contain sensitive data. GitHub provides [this helpful article](https://help.github.com/articles/generating-a-new-gpg-key/) on generating GPG keys. You can also find this handy guide on creating the perfect [GPG KeyPair](https://alexcabal.com/creating-the-perfect-gpg-keypair/). It's a ton of detail, so I don't want to bog you down too much. Research the pages in your free time and learn how you can easily put these to use!

#### Kali Linux
Want to take your security a step farther? I highly recommend looking in to [Kali Linux](https://www.kali.org/). This distribution is maintained and funded by Offensive Security. In addition to Kali Linux, these guys also maintain the [Exploit Database](http://www.exploit-db.com/) and the free online course [Metasploit Unleashed](http://www.offensive-security.com/metasploit-unleashed/Main_Page). Now, I haven't messed with any Linux distro myself, but I certainly plan to in the near future, and this may be one of my first go-tos. It's topnoch in security and privacy, so check it out if you're in to Linux!

#### Oracle VirtualBox
Oracle VirtualBox is a tool I've been meaning to play with for a while now. So I will be doing just that here soon! A virtual box creates and runs a "guest" OS in a window of the host OS. It provides a self-contained environment to experiment with new software without risking damaging changes to the host OS. It's a pretty unique tool. You can find a full guide to run Ubuntu through it [here](https://linus.nci.nih.gov/bdge/installUbuntu.html). This runs in a "sandbox" instance, which can be usefull for tracking down and analysing malware. It could of course provide other security benefits, preventing you from getting other unwanted malicious software installed on your PC.


Again, these last few areas are generally for more advanced users, software engineers and high target work places. It is very much worth the time to research it and see what works for you and for what situations, especially in a time that privacy and personal data has become so easily accessible. My current steps follow, of course, a Password Manager and Multi-Factor Auth, as well as SSH. I will be looking in to using GPG and in the near future Kali Linux. Until then, VirtualBox will soon be my new home for a short while. With that, I highly encourage EVERYONE, even every-day average users, to research and practice better security. Your privacy, whether you see it that way or not, IS IMPORTANT. Be diligent, have fun, and stay safe!
