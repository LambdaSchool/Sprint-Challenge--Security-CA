# Threat Model

_Introduction_

The **threat model** is a model of how an _attacker_ can access your
personal information, confidential information about **you**. There are four
facets to a threat model, _modeled_ below.

## Attack Surface

_Introduction_

The **attack surface** of a threat model are the entryways in which an attacker
can bypass your personal security.

_Physical Examples_

* your computer: an attacker can access your personal information,
  confidential information, etc. through your physical computer, namely
  your persistent storage (e.g. hard drive) and RAM (before it is cleared).
  Your computer / laptop is an **attack surface** that is as strong as your
  login password / app passwords / hard drive encryptions (or lack thereof).

* a "notebook" of passwords or other relevant security info: if you have
  a notebook or "_paper form_" of passwords (either in plain text or ciphered)
  or other security info (such as birthday, birth location, answers to
  security questions for bank accounts, social media, etc.), these things can
  be utilized by an attacker to gain access to personal information. Storing
  these things in a safe, safety deposit box, or secure medium **decreases**
  the likelihood of _penetration_, or the "toughness" of the **attack surface**
  but it doesn't remove the **attack surface**. If it exists, it is an **attack
  surface** that needs to be considered in the threat model.

* In general, anything that is physical and can be taken, utilizied in the
  physical world **and** has information relevant to bypassing your
  security, is a _physical_ **attack surface**.

_Electronic Examples_

* email: your email not only has information about yourself and what places
  an **adversary** / attacker can attack, but also the ability to reset your
  password for said places. This means that your email is an **attack surface**
  that can potentially be very deep (if not walled off properly with e.g. 2FA.
  More info about this can be found in **Mitigation**).

* your computer: an attacked can gain access to your persistent storage and
  RAM on your computer through the Internet (this is electronic vs physical in
  the previous example concerning your computer). Your computer's electronic
  **attack surface** is sometimes larger than your physical computer because
  an attacker can very "quietly" access your computer's information through ports
  and other backdoors (via malware/rootkits, more info found in
  **Attack Vectors**) whereas a physical attack surface needs the physical
  computer, which may sometimes be obvious (e.g. if your laptop goes missing).
  For an electronic attack surface, your laptop only needs to be connected
  to the Internet (or LAN e.g. at a workplace) to be attacked / hacked.

* servers: not directly in your control, but if hosting servers are compromised
  (such as social media, email), hackers can gain access to your
  (and many others) personal information.

* In general, anything that involves the Internet and electronics and has your
  personal information is an _electronic_ attack surface.

## Adversaries

_Introduction_

Your **adversaries** are anyone who may want to compromise your personal
information.

_Examples_

* a hacker who wants to exploit / ransom your information for financial gain.
* a competing firm who wants to damage your reputation to gain your clients.
* your coworker that has a resentment toward you. Note: your coworker and
  a hired hacker may coconspire together against you to both benefit
* In general, **adversaries** may be very close to you (coworkers, even
  "loved ones"), or they may be very far removed (random hackers / pranksters
  halfway across the world). Regardless, knowing who your adversaries might be
  can greatly help in **mitigation** (discussed later).

## Attack Vectors

_Introduction_

**Attack vectors** are the avenues in which attackers gain access to your
perssonal / financial / confidential information. These **attack vectors** are
used on an **attack surface** (described above).

_Examples_

* physical computer: if your computer isn't locked up (e.g. Kensington lock) or
  stored under lock and key (like in your home vs left in an open coffee shop
  accidently), or not "locked" in the OS when you're away, an **attack vector**
  is for an attacker to physically go on your computer and take / view your
  confidential / relevant files. Think of the movie/ TV heroes copying the
  contents of a computer / server onto a USB (because the villains didn't
  connect their secret computers to the Internet for security) to use to find
  more info or verify the villain's wrongdoing. This is a _physical_ **attack
  vector**.

* computer: an _electronic_ **attack vector** is the primary method, though,
  for that random hacker / prankster will use to exploit, ransom your info.
  **Attack vectors** here include backdoors, keyloggers, malware, brute forcing
  your passwords, email phising, website misdirection, among many others.
  An important part of **mitigation** is strong password creation, 2FA, and
  compartmentalization (all discussed later).

* plain and simple surveillance: your password may simply get compromised
  because they are looking at the keys (or recording) you're typing when
  you type in your password for your bank account login, etc. This is why
  2FA and a password manager are so important (discussed in **mitigation**).

## Mitigation

_Introduction_

**Mitigation** is how you protect yourself against attacks. This is usually
done by reducing your attack surface, strengthening your attack surface,
compartmentalizing (or reducing depth of sttack surface / walling off), among
other things.

* Reducing your attack surface: having many social media / other accounts
  on the Internet can lead you to trying to defend a lof of "fronts".
  There is always a trade-off though. You may need all of your accounts.
  If this is the case, then you must strengthen and compartmentalize your
  attack surface.

* Using a password manager: using a password manager allows you to
  a) generate strong passwords (ones that will take too long to brute force)
  and b) keep your passswords in one place for convenience. There is always
  a trade-off. This creates a very deep, not-compartmentalized attack surface.
  The way to remedy for this is to create a very, very, very strong password
  for your password manager master password. And keep that password stored in
  a very physically-secure, and hidden location (such as a bank safety deposit
  box).

* Strengthening your attack surface: especially in regard to computers, you can
  strengthen your computer's electronic attack surface by installing a
  reputable Internet Security Suite Software, which will include antivirus,
  firewall, some kind of heuristic software to detect rootkits and
  hidden malware.

* Using 2FA (or two-factor authentication) can help wall off or create an extra
  layer of security for logging in to your "secure accounts"
  (e.g. bank account). This makes a _physical_ requirement for logging in (such
  as your phone or USB key).

* In general, **mitigation** is a trade-off of security and convenience. It
  would be **inconvenient** to have to go to the bank every time you wanted
  to unlock your password manager to log in to your bank account (because
  your password was too long / complicated to remember). It would be
  very convenient to have this very long and complicated password written down
  on your fridge to access anytime. But it would also be very **insecure** and
  basically useless to have chosen this long and complicated password.

## Conclusion

A **threat model** can help you (yes you!) patch vulnerabilities in your
personal, confidential, financial, etc. securities. By looking at your **attack
surface** and **attack vectors**, you can reduce your attack surface,
strengthen them your attack surfaces through helpful software and knowledge
about the attack vectors, compartmentalize your secure info through walls,
create extra barriers through 2FA, all of which **mitigate** your data
penetration from your **adversaries**.

I hope this has been a helpful intro to the **threat model** and you'll think
about and implement the recommendations written here!

Cheers!

Sam
