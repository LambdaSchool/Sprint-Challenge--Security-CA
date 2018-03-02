# Practical Security

Do something to improve your personal security setup - if you’re not using a
password manager, set one up. If you’re doing that, then set up two factor for
some of your accounts. If you’re doing that, then set up proper SSH keypairs for
services that support it (e.g. GitHub). And you can keep going - set up a GPG
keypair, consider simple dedicated hardware for second factor, set up a trusted
computer/VM running only open source software, set up a "sandboxed" environment
for web browsing that doesn't save state, etc.

Use the practices and approaches we learned about this week - this means pick
a suitably long _passphrase_ to protect your password manager, and think about
what your threat model is and what services you want to trust with what
information. Some general tips:

*   You are a software developer, which means you're a high value target (you are
    a potential attack vector to anyone who runs your code)
*   Unless you're working on something controversial for the political regime you
    reside in, the NSA/Mossad/KGB/MI5/etc. are probably not your adversaries
*   The sorts of threats you _should_ worry about - common criminals/organized
    crime, botnets, malware, extortion (stealing your files, DDoS-ing your service)
*   For deciding whether or not to trust a service, consider history, reputation,
    and incentives, as well as what countries it operates in (which will impact the
    laws it is subject to, both in terms of disclosure and potential damages)

Some resources/goals:

*   [KeePass](https://en.wikipedia.org/wiki/KeePass) - open-source password manager
*   [Alternatives to KeePass](https://alternativeto.net/software/keepass/) - cloud, desktop, etc., consider your personal security/convenience tradeoff
*   [Two Factor Auth](https://twofactorauth.org/) - list of services that support 2 factor authentication
*   [Connecting to GitHub with SSH](https://help.github.com/articles/connecting-to-github-with-ssh/) - more convenient (for command line) _and_ secure than passwords
*   [Adding GPG to your GitHub account](https://help.github.com/articles/generating-a-new-gpg-key/) - simple GPG setup that will let you sign commits
*   [Creating the perfect GPG keypair](https://alexcabal.com/creating-the-perfect-gpg-keypair/) - more complicated, for those who want finer control
*   [Keybase](https://keybase.io/) - a way to share/certify public keys (also offers encrypted chat, file storage, etc.)
*   [Yubico](https://www.yubico.com/) - affordable hardware security devices for two-factor/crypto
*   [How to install Ubuntu in VirtualBox](https://linus.nci.nih.gov/bdge/installUbuntu.html) - usable secure popular distribution of Linux
*   [Kali Linux](https://www.kali.org/) - security-specific (penetration testing) distribution of Linux, includes VM images for download
*   [Information about Sandboxes](<https://en.wikipedia.org/wiki/Sandbox_(computer_security)>) - general starting point for learning about sandboxes to contain an application

After you do some of the above, write 1-2 paragraphs summarizing what you did
(remember, a good security setup doesn't depend on security through obscurity,
so it should be safe to talk about it as long as you don't share actual
passwords/secrets). As a stretch goal, write a blog post about your security
setup describing what you’ve learned and tips you have for others.

Currently I already have a different password for each place that I register at. I already use lastpass, and I enable 2FA anytime a website offers it. I have knowledge and experience using PGP and I aready have a public key available to anyone who did want to use it. Whenever it is available, I verify and check checksums of new software that I install. I never install software that I dont know about or research thoroughly. The one and only major change that I have made to my passwords is the recommendation of pass phrases. Instead of a variation of a word with numbers and symbols, I now use 5 random words with spaces included. Note that a lot of website don't allow for long passwords, but when I went down the list of lastpass passwords, I did the ones that could. I also know that lastpass offers free random password generation that is supposed to be secure, and they will even change every password for you on all accounts you have. BUT I personally don't feel safe with that. I worry that if I lose access to my last pass and I have a bunch of passwords that are encrypted gibberish, that I may not be able to recover those accounts. Another method that I know about is hardware based security. Although I too worry I would lose the usb driver or magnetic card etc..
