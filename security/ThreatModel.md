* ThreatModel: Risk of compromising your AWS account credentials.
* Attack Surfaces
  * Github
  * Your PC where you ssh file is stored in home folder
  * AWS itself
* Adveresaries : Hackers who want to use your AWS resources and inflict financial losses to you.
* Attack Vectors
 * Crawling through your Github repo for security key.
 * Fishing to install malicious software on your PC

* Mitigations
 * Use config file for github repo and .gitignore the security credentials that your project is using
 * Have two factor authentication for your home and root folder
 