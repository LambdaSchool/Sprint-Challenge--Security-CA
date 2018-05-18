## Threat Model Assessment

Coworker *(insert name here)*,

I've been thinking of a potential threat for our software development in-house team, and have developed a threat model after assessing the situation.

### Situation

The situation consists of an `attack surface` (how we're exposed to an attack) via our company's routers. Adversial nations (and individuals) have been devising means to hack into wifi routers, as mentined here - [Cyberattacks in U.S. Homes and Businesses]("https://www.usatoday.com/story/news/2018/04/16/russia-sponsoring-cyberattacks-u-s-homes-and-businesses-u-s-and-u-k-officials-warn/520981002/").

`Attack vectors` (how we may be compromised) include defualt or weak password on the router, weak or no firewall, using an old encpryption scheme, or out-of-date firmware. Once compromised, malware can be installed to gain access to other devices (like our phones, computers, and wearables) to steal information, and set up for future attacks.

### Mitigations

What I suggest:
- Make sure the wifi password is secure
- Install a secure firewall if there isn't one
- Update the encrpytion scheme and / or the firmware

Doing these things will make sure we as a team can move forward in a more **secure** developer invironment.

A concerned developer on the team,

*Tyson Williams*