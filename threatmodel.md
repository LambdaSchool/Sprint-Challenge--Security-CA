Welcome, *Gail!*

On your first day as developer at Soolo, it's best you get a quick intro to our security policies and actions we take to assure our app is a safe place for users online. At Soolo, we provide a platform for fashion designers, dressmakers and tailors to properly organize client profiles, inventories and business transactions. 

User security is a must, and how we assure that Soolo not only provides the best service, but enough security to put our consumers at ease.

---

### Users at Soolo

| Users | Information they store |
| ----- | ----- |
| *Clients* | Personal measurements, financial and client information, images that could be shared online. | 
| *Suppliers* | Inventory, financial and client information, images more likely to be shared within Soolo than third party sites. |
| *Stores* | Client measurements, financial information, images also likely to be shared on third part sites. |


##### Attack surface

Soolo takes in alot of user input: we have their financial information (credit card, lists of transactions they have conducted, items they have purchased, users they have communicated with, lists of their messages exchanged, etc). We will be using third party payment services (Paypal) as an alternative. Our payment system, however, takes in credit card and identity information.

Our database keeps a long list of users (entrepreneurs, suppliers, clients). Our users are allowed to constantly update their information as well.

Our app will be stored on different browsers and will be available in mobile. We need security that takes mobile devices into consideration, as well as the security of the various networks, public and private, the user may be login into while internet surfing.


##### Adversaries

Multiple platforms include plenty hackers who will attempt to steal personal user and company information. 

Our increased number of developers can also be a factor we need to consider. Background checks are always shifting, as newer ways of hacking are developed. 

We may also have users who are fake and whose main purpose could be to exploit real users on our app. 

Advertisers could be a potential threat. Some ads are used purposely to lure users away from the app, and have them give away personal information.

##### Attack vectors

- *Password theft* - hacking into user accounts by using their password.

- *Database content* - breaching into database to steal information

- *User interaction with fake accounts* - fake users and advertisers can mock our app interface to take information. The can also interact with out clients and take their information. 

- *Direct breach from an inside source* - refer to database content, password theft

##### Mitigations (what can be done to reduce the risk, e.g. 2-factor auth, encryption)

- *Password theft*
    Users can use password that matches our criteria:
        1. Must be a different password 
        2. Must be made of different characters
        3. All paswords hashed
        4. Login session heavily authenticated

- *Database content/files*
    Heavy encryption of content and files in our database.

- *User interaction with fake accounts*
    1. Monitor fake accounts with reports sent from users
    
    2. Tracking users who do not have alot of information on their accounts. 

    3. Mini background check - Have users give enough information to provide an authentic profile. (E.g, using capture tool to ensure they are real, having them give us bank information and checking if the bank does have an account with the user).

- *Direct breach from an inside source*
    1. Company rolling background checks for all incoming employees. 

    2. Limit information to the requred group of employees in charge of app security. Use proper database services. 