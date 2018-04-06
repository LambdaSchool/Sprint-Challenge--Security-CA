# Part 1 - Understand and Communicate a Threat Model

Think of a threat model - a situation with a user (or type of user) and a
context that frames their personal security preferences and situation. Concepts
you should consider (and a few examples of each) include:

- Attack surface (what tech/situation exposes them, e.g. systems they use, places they go)
- Adversaries (who may be interested in compromising their security, e.g. criminals, pranksters)
- Attack vectors (specifically how they may be compromised, e.g. password theft/cracking, surveillance)
- Mitigations (what can be done to reduce the risk, e.g. 2-factor auth, encryption)

Write a summary of the overall situation as if you were going to send it as a
professional email to explain it to a coworker. Please turn in a file
`ThreatModel.md` with 1-2 paragraphs addressing the above concepts in a concise
fashion.

I am writing a general overview to describe a threat model for a new online banking application that my bank has asked me to overview from a security point of view. 

We will look at this security model from a few different angles

Attack surface : how my possible security weakpoints are there that can compromise the system ?
Adversaries : who are the type of people that could target the application 
Attact vectors : what are different type of attack that could be implemented
Mitigations : what can we do to block or minimize  the serious  damage of breach

The Attack surface will of course mainly be through the web app authentification system. We recommend that two factor authentification to ensure that if passwords are compromised the attacker will need another physical access point belonging to the user. We would encourage you to consider sending random verifible text numbers to the users who will use it along with their passphrase when loggin in

All website traffic should be secured and encrypted using htttps . On the backend passwords should be hashed and salted.

Sessions should be timed out after a short time of activity. For withdrawls and transfers the user should have to input a new text just sent to their phone before 
carrying out the transaction. 

We would recommend algorithms and machine learning to monitor recent and live transactions  to flag up unusual customer banking transactions for possible fraud and contact the customer. Confirmed attacks should carefully analysed to see if other customers may have been affected and how we can further mitigate this attack

We would view a broad range of people and groups as attack threats. Crimminal gangs and very technial hackers would be the main threats

We will engage with major banks in this and other countries to get an overview of their implementations and advice and updating our proposed model accordingly. 

We look forward to hearing from you and working with you further. 

Yours sincerely 

Bernie Madeoff 



