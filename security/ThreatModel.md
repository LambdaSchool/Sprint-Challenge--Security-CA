1.  Think of a threat model - a situation with a user (or type of user) and a context that frames their personal security preferences and situation. Concepts you should consider (and a few examples of each) include: Attack surface (what tech/situation exposes them, e.g. systems they use, places they go) Adversaries (who may be interested in compromising their security, e.g. criminals, pranksters) Attack vectors (specifically how they may be compromised, e.g. password theft/cracking, surveillance) Mitigations (what can be done to reduce the risk, e.g. 2-factor auth, encryption) Write a summary of the overall situation as if you were going to send it as a professional email to explain it to a coworker. Please turn in a file ThreatModel.md with 1-2 paragraphs addressing the above concepts in a concise fashion.
    _Answer_

Dear Client,

The purpose of this correspondence is to provide a threat model related to your internet-facing web and mobile application. This application features inventory and customer accounts with a SQL server back end.

# Attack Surface

Your _attack surface_ includes the sum of real and potential vulnerabilitie across all software, hardware, and networks.

# Adversaries

Potential adversaries include vandals, pranksters, common criminals, identity theives, corporate rivals, and to a lesser extent, foreign and domestic government entities. All of these could potentially be motivated to harm your business model, profit margin, and/or corporate reputation.

# Attack Vectors

In your case, potential attack vectors are many. Some of these include, but are not limited to:

1.  Denial of Service Attack -
    A powerful central source, or more commonly these days, a wide distribution of infected machines/devices could potential concentrate traffic and overwhelm your applications, systems, or networks.

2.  Human Misuse -  
    Inside or external attackers could potentially gain access to or misuse credentials to harm or otherwise compromise your applications, systems, or networks.

3.  Crimeware -  
    Crimeware is any software that is installed within applications, systems, or networks through internal (i.e. locally installed) or external (i.e. email attachments, etc) means for nefarious purposes. Recently, the most common form of crimeware is _ransomware_, which is software that removes the user's access to data until such time a ransom is paid.

# Mitigation

A key to mitigating risk is keeping one's attack surface small, and properly managing the interaction between software, hardware, and networks. In terms of software, a small attack surface also provides the added benefit of a clean and efficient UI.  
Basic policies that establish good password/passphrase practices, ensure the physical safety of high-vulerability areas, and cross-delegation of security responsibilities will go a long way toward mitigating risk.
