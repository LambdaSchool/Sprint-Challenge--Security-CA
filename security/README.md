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

-----BEGIN PGP PUBLIC KEY BLOCK-----

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
icXgRonJ
=wMBY
-----END PGP PUBLIC KEY BLOCK-----
