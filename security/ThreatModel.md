## Threat Model

To: Coworker
Subject: Threat Model- Banking Application

    Upon the release of (SOME BANK)'s new mobile application, our team should look at the threat model 
for said application. By doing so and taking the proper precautions we will hopefully ensure the Users privacy and secruity remains as safe as possible.
The User, anyone using the banking application, should be provided with a trustworthy and convenient product, one that not only makes their busy life easier, by providing convienient on the go banking, but also protects the information they might not want to share. The goal of setting up these precautions would be to prevent the User's Adversaries, criminals who want the Users banking information (i.e. account number, access to funds in the account etc.) from being able to log in to the banking applicationa as the User.
One main attack surface that I'd like to bring up is the users mobile device itself. Should the User's phone be stolen we wouldn't want the application to be easily accessed by the adversary. A mitigation for this would be for the user to select an 8 digit security key that they would enter after loginng in with their password. While the mobile device is probably proctected with its own security key- in the off chance that the adversary cracks that code- we wouldnt want them to have instant access to the Bank Application. Furthermore, while the application is already password protected, this extra security key would be another code that said adversary would have to crack, thus making it harder for the person who stole the pone to have access to the application.
Another attack vector I'd like to handle is phishing attacks- lets say the adversary doesnt have the physical phone but instead sends an e-mail to one of our users -pretending to need their username and password for something that has "gone wrong" with their account. The extra security would be a great mititgation for this as well. However, for an extra layer of protection we should also think about using 2 factor authentication for use with the web-based application.




