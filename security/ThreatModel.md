# Threat model

Following are some potential threats to a Django app. I will try to mitigate as many as possible.

## Generic Description of Target Web App

To provide a service to users which respects their privacy, Data should only be available to those who the user explicitly selects. This
excludes the application owners by default. 

### Potential threat sources

* Application administrators
* Data loss (laptop left unattended)
* Automated attacks
* Nation states
* Friends / family

### Major threats

* *Theft of entire database:*
    * Application admins - dump data from database
    * Data exposure - Misconfiguration, accidentally exposed backup/dump, lost USB stick
    * Automated attacks - SQL injection, XSS exploits (application-level attacks)
    * Nation states - being compelled by law
* *Theft of individual auth credentials:*
    * Friends / family / partners - offline theft of login details
* *Server compromise:*
    * Automated attacks - Network-level access, SSH access.
    * Application admins

### List of potential Attacks

* Admins dumping database [mitigation goal: **complete**]
    * Encrypt sensitive data using secret known only to the data owner.
* Accidental data exposure [mitigation goal: **complete**]
    * Encrypt sensitive data using secret known only to the data owner
* Network-level unauthorized server access [mitigation goal: **partial**]
    * Data-theft would require the interception of the user's secret.
      *Alternative: Network-level security*
* Administrator authorized server access [mitigation goal: **partial**]
    * Data-theft would require the interception of the user's secret
      *Alternative: Operational partitioning (i.e. minimize access)*

Encryption could be done either on the client using JavaScript, or on the server, but there is no added benefit to performing the encryption on the client - therefore encryption should be performed on the server.