# Part 2 - Practical Security

Do something to improve your personal security setup - if you’re not using a
password manager, set one up. If you’re doing that, then set up two factor for
some of your accounts. If you’re doing that, then set up proper SSH keypairs for
services that support it (e.g. GitHub). And you can keep going - set up a GPG
keypair, consider simple dedicated hardware for second factor, set up a trusted
computer/VM running only open source software, set up a "sandboxed" environment
for web browsing that doesn't save state, etc.

Use the practices and approaches we learned about this week - this means pick
a suitably long *passphrase* to protect your password manager, and think about
what your threat model is and what services you want to trust with what
information. Some general tips:

- You are a software developer, which means you're a high value target (you are
a potential attack vector to anyone who runs your code)
- Unless you're working on something controversial for the political regime you
reside in, the NSA/Mossad/KGB/MI5/etc. are probably not your adversaries
- The sorts of threats you *should* worry about - common criminals/organized
crime, botnets, malware, extortion (stealing your files, DDoS-ing your service)
- For deciding whether or not to trust a service, consider history, reputation,
and incentives, as well as what countries it operates in (which will impact the
laws it is subject to, both in terms of disclosure and potential damages)

# Personal Security

* All passwords encrypted and managed through TrueKey by Intel. It has a random password generator for every site that I visit.

* My passwords are rotated weekly to another randomized string. All of these passwords are written in a notebook encrypted by a cipher that requires a certain group of books and knowledge of the cipher to decode. Even if they can decode it, it will be difficult to determine if the randomized passwords are correct. It will not have names or any common factors to reference. Pretty sure I learned this from National Treasure or The DaVinci Code.

* I have two-factor on all of my accounts. My bank asks a series of questions and requests a pin above my password.

* On my iPhone, many of my apps require touch authorization or pins to access. So, even if you break into my phone, you then have to break in to my apps.

* I am working the SSH pairs for GitHub.