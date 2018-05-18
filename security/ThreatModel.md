# Security Threat Model

The application is a Web application with a Python and MySQL Server back end and React.js for 
the front end. The Web server is located at the company's headquarter. 
Business and data access logic resides on the Web server to lower cost due to the high volume of transactions.
The application enables Internet users to browse and purchase products from the company's product catalog
and also host other's client web stores. The company saves the credit card numbers.


- Attack surface (what tech/situation exposes them, e.g. systems they use, places they go)

    One of the expose situation could be a physical catastrophe into the building doe to natural disasters
    such a earthquakes, floatings etc. this could really delay the service restore.
    The actualization for server security patches: if the personal of operations are not constantly checking and updating
    new common security threats could lead to leave a time frame where attacks can be perform against the company.
    Since all the sites hosted in the servers are shopping carts they have forms like login, sign-up, and payments.
    

- Adversaries (who may be interested in compromising their security, e.g. criminals, pranksters)

    Hacker who want to steal credit card numbers.
    Hackers who may want the customer emails to perform fishing or try to buy in behalf of the user.

- Attack vectors (specifically how they may be compromised, e.g. password theft/cracking, surveillance)

    The company could be compromising users information such a credit cards and emails.

- Mitigations (what can be done to reduce the risk, e.g. 2-factor auth, encryption)

    Move the servers to AWS or a hosting service that could provide a very high level of security and easy way of back up information.
    This will mitigate the physical server threads.
    Pay per use: this implementation has to be done in both the server and the code to minimize server request 
    and only pay for the traffic and request from sites that are really been used. This could be achieved implementing 
    cache services.
    Use of https across sites to mitigate hacker attacks. 
    Use a service gateway for payments where they save the credit cards number so the company only saves a reference token
    for future transactions.
