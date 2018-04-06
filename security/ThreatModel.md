Lillian,

In light of the recent security breach at our competitor, we will be setting a time for the team to meet and discuss security measures and best practices at our firm. As you know, we have the responsibility of helping millions of customers with their fitness needs by providing a world-class mobile app that allows users to track calorie intake and exercise. Because of the recent breach at Under Armour, it is imperative that we do everything to protect the data of our users and this firm.

Please review the following information I've compiled about the recent UA incident so you can be prepared for the meeting on Monday about how we can prevent similar events from occurring here.


----
#### Under Armour's _My Fitness Pal_ app breached
##### Scope of the Attack #####
150 million user accounts compromised

##### Attack Surface #####
Mobile app was targeted, stored data was leaked, including usernames, email addresses, and hashed passwords

Because premium account payments there are processed through the Google Play store, no payment information was stored.

Purchases of other Under Armour products navigates the user to the main UA site, so no payment information was stored.

Security here is a major concern---the app was purchased by Under Armour in 2015. We do not know all the details, but we know that UA was in the process of moving passwords from a SHA-1 hash to a bcrypt hash. The bcrypt passwords that were compromised as still considered secure, even in the hands of the hackers. Because of the crypt, users could be alerted and have time to change their passwords without having to be overly concerned about any other shared password accounts being compromised. 

The same cannot be said of the users who were still under SHA-1. This hash has been under fire for the last decade, and it is the recommendation of many security experts that this hash no longer be used to protect sensitive data. 

Likely the Lee family founders used SHA-1, and when UA acquired the app, started making changes to update the security for users. However, this was not done quickly enough, and users are the ones who will suffer. As, likely, will the share value of UA.

##### Adversaries #####
The most pressing concern is that of criminal adversaries, who want to gather sensitive user information for malicious intent. The information about users could also be worth money to criminals looking to sell user data, as the fitness industry is a multi-million dollar business.

Pranksters seem unlikely here, as no self-respecting Anarchist could have good reason to target people trying to reach their fitness goals. It is possible, however, that a prankster could want to disrupt the service offered by shutting down the services for a period of time. If that prankster has been hired by a competitor to shut down operations for the benefit of a rival, that could also occur.

##### Attack Vectors #####
While customers who use insecure passwords could be guessed by outside parties, customers have a very limited scope of what they have access to. It is still vitally important to scrub any data that a user may input, to make sure that any malicious intent is not given the chance to infect the greater system through a user's input.

Of vital importance, of course, is that the employees of the firm are following best practices for security. Secure passwords must be maintained, as well as training on not clicking suspicious links, reporting spam and phishing emails, and not opening up attachments from suspicious or unknown senders.

Having an outside IT firm that are specialists in their field is also a beneficial way to make sure there are no in-house leaks that are being overlooked.

##### Mitigations ######
In light of this, we must make sure we are making the following implementations at our firm:

- Do not store unneeded data, outsource logins  with OAuth so we do not have to store passwords at all, and creates a streamlined experience (since users already make purchases with Google Play)
- Any NPMI (Non-Public Material Information) stored about customers should be hashed using a respected algorithm
- Regular security training in the office
- Make sure employees are following secure password practices, including instituting minimum lengths of passwords
- Regular security audits by trained and competent secure experts
---


Thank you for taking the time to read through this, Lillian. I look forward to meeting with you and the rest of the team on Monday to being implementing the highest security possible for our users.



Enjoy your weekend, 

_Abby Tiffany_