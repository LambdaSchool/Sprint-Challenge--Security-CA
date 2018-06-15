# Threat Model - Mom and Pop Shop

Dear Smith,

As technology advances the web, and mobile development, food establishments continuously have new potential avenues of buisness opening up that they must capitalize on to stay competitive and relative. Two big concepts right now are mobile orders, and delivery services. Examples being Doordash, Grubhub, Uber Eats, and Postmates. Each requiring their own account management, and the store may even have online ordering on it's own website additionally. 

A large amount of local buisnesses are run by older generations who may not have grown up around technology, and smart phones, and as such may not be very knowledgeable on the most secure practices when managing all these separate accounts. They more than likely use one buisness email for each account, and who knows how they keep track of their passwords, or if they even have different secure passwords for each account. Establishments started by younger people have a definite edge, and could use their knowledge of technology malicously to get ahead of their competitors.

So for a local buisness run by an older individual / couple, here is a likely threat model.

* Attack Surface:
    - They most likely have one computer in the back of the store that they do all of their management from.
* Adversaries:
    - Disgruntled employees
    - Disgruntled customers
    - Competing buisnesses
    - Third party employees (Hired by the mobile services)
    - Ransom hackers.
* Attack Vectors:
    - If passwords are easy to guess, or they use the same passwords.
    - If the computer itself is always logged in / unprotected.
    - Liberally giving out passwords.
    - Social engineering.
    - Data loss / ransoming.
    - Only computer being damaged / destroyed.
    - If the store uses wifi, insecure connection.
    - Security ignorance on the part of management and/or staff.
* Mitigations:
    - Password manager / secure passwords.
    - Only giving passwords out to other trusted management staff.
    - Locking the computer out when not in use.
    - Only allowing trusted employees to be around the computer when passwords are being entered / confidential information is being displayed or managed.
    - Backing up data, encrypting data.
    - Having another secondary computer or mobile device that only the owner has access to.
    - Secure wifi connection, or a wired connection.
    - Up to date security training for management and staff.

From,
Brett