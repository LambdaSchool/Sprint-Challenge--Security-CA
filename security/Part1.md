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

SITUATION: Under Armour's My Fitness Pal App is Targeted - 150 million user accounts compromised

ATTACK SURFACE: Mobile app, data is stored, such as usernames, email addresses, passwords.
            Payments are processed with Google Play account, so no payment information should be stored
            Any purchases of UA products you are navigated to the main UA site
            UA claimed initially to have used BCRYPT to hash PWs, which is great, leaked PWs still have protection that is strong
            Some of their PWs were only hashed with SHA-1, which is inferior and is unreccommended for securing PWs

            UA acquired the company from the founders in 2015, when it likely started assessing the heightened security measures that needed to be taken.

ADVERSARIES: Criminals may want to gather private data of users for malicious intent. Pranksters seems more unlikely, but they could want to disrupt the service offered and shut down the service for a period of time
ATTACK VECTORS: Probably the most direct way in would be to target employees of UA who have access to the servers on which data is stored. It has been suggested that UA keeps many of their IT-dept work in-house. Outsourcing your IT work seems like it should be less secure, but going to specialists who are trained and extremely knowledgeable in their field can actually grant you better services provided, and a more secure service to offer customers.

The company may have had inferior protections for customers in the past. If they were in the middle of upgrading passwords from SHA-1 (which has been debunked for the last DECADE) to something more secure like BCRYPT, it would be vulnerable where those changes had not yet taken place--imagine a softshell crab before it's new skin has totally hardened up.

MITIGATIONS: Hash stored data using the most secure crypts available.
            Do not store unneeded data--outsource when possible
            Should have been able to outsource login using OAuth, which would have meant there were no passwords to steal--like they outsourced their payments to Google Play
            Make sure the passwords are a certain length, longer than 8 chars!!
            Make sure that employees are following secure password practices
            Regular security audits by trained and competent secure experts