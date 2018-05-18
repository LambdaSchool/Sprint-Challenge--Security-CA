# Part 1 - Threat Model

```
Richard is data analyst working for a major political party. It is currently election season and he is working the campaign for a powerful but unpopular major political figure.

He lives in Washington D.C in a residential neighborhood where most of the other inhabitants also work in politics.
```

### Attack surface

Richard uses a variety of personal electronic devices (phone, tablet, laptop) as well as a work laptop, which he sometimes brings home with him or travels with. All of these devices, as well as any physical correspondence or documents, would be a target due to the sensitive nature of his job.

### Adverseries

Richard would be targetted by a wide variety of adverseries due to his work. This would include, but not be limited to, political adverseries within his own part; political adverseries within other political parties; domestic intelligence agencies; foreign intelligince agencies; private security companies hired by private interests. This is in addition the usual online security threats that affect the average person (phishing, scams, identity theft etc.).

### Attack Vectors

Due to the sensitive nature of his work and the large resources available to many of his potential adversaries, Richard should expect every method available to be used against him.
In addition to remote methods like password cracking, malware, keylogging that target his devices etc, he should also expect more traditional methods such as physical breakins, surveillance, eavesdropping etc.
People close to him may also be targetted as a way to get to him as well. Additionally, he may be used in order to compromise the security of someone else, such as his employer or colleagues, which may be an even higher threat.
IoT devices in Richard's home, workplace or other places he frequents may also be used as an attack vector.

### Mitigation

Since some of his adversaries have deep pockets and would have the motives to throw considerable resources towards compromising his security, Richard should assume that his devices will be compromised.

To mitigate this he should keep anything that is hyper-sensitive in hard copies and/or on airgapped machines. Depending on the information, he may even want copies left with trusted individuals (such as a personal attorney) with instructions in the event his personal safety is compromised as 'insurance'. He should hire a thoroughly vetted and trusted security expert check his machines regularly for malware, as well as give recommendations for managing his security on his personal devices (password management, encryption etc.).

He should use encrypted communications with machines not associated with him (i.e. purchase of machine cannot be traced back to him) for highly sensitive communication. At the same time he should maintain appearances with his regular devices. If someone is surveilling him and notices a lack of normal activity they will be more inclined to look more deeply. 'Security through obscurity' is also a concept Richard regularly employ since he should assume that he is, or can be, compromised.

Richard should make sure he doesn't have IoT devices in his home, and be wary of doing anything that may potentially compromise his security when in environments that do. He should also never use any kind of public wi-fi, and should also consider using a VPN service.


# Part 2 - Practical Security
In order to improve my personal security I spent some time setting up a password manager to manage my accounts. Previously I had a system that used a few different passwords that I used for all my accounts. I had one password that was easy to remember that I used for a variety of low-priority accounts, one password for medium priority accounts, and one for higher priority accounts. I decided to setup the password manager to handle the low and medium priority accounts. For the high priority accounts I opted to continue using my existing secure passwords for now while I trial run the password manager.

I also setup two factor authentication on some of my accounts that didn't already have it enabled. In addition to that I researched alternate email providers and created an account with one that uses end-to-end encryption and is open source.

I also started researching linux distributions as i've been interested in bulding a linux machine after using macs exclusively for the past decade plus. I was surprised to learn that Ubuntu has (or had) spyware installed and will be sure to avoid that. Arch Linux seems to be the most compelling to me so far and seems to be good as far as security goes.
