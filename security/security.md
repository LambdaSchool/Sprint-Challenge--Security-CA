
# Threat Model:

### Step 01: Decompose the application
* How does the app interact with external entities?
* create use-cases to understand how the application is used, 
* identifying entry points to see where a potential attacker could interact with the app
* identifying assets (i.e. items/areas that an attacker would be interested in
* identifying trust levels which represent the access rights that the app will grant to external entities

###### Data flow Diagrams (DFDs)
* The Threat Model Document will inform the data flow diagram (DFD) for the app. 
* DFDs show the different paths through the system, highlighting privelege boundaries. 
* DFDs help to identify the potential threat targets from the attacker's perspective, such as:
  * data sources
  * processes
  * data flows
  * interactions with users

### Step 02: Determine and rank threats.
* Create a Threat Categorization Methodology 
* A threat categorization such as STRIDE can be used (identifies threats from the attacker's perspective)
* Or the Application Security Frame (ASF) (identifies threats from the app's defensive perspective) that definies threat categories such as:
  * Auditing & Logging
  * Authentication
  * Authorization
  * Configuration Management
  * Data Protection in Storage and Transit
  * Data Validation
  * Exception Management
* Create "threat trees," each with their own "threat root system." One threat tree is made for each threat goal
  * From the defensive perspective, Application Security Frames (ASFs) identify the threats as weaknesses of security controls for such threats. 
  * Common threat-lists with examples can help the identification of such threats.
  * Use-&-Abuse cases can illustrate how existing protective measures could be bypassed, or where a lack of any protection exists.
  * The determination of the security risk for each threat can be determined using a value-based risk model such as DREAD
  * A less subjective, more qualitative risk model based upon general risk factors (e.g. likelihood, impact, etc) may be used instead of DREAD

### Step 03: Determine Countermeasures and Mitigation
* Such countermeasures can be identified using threat-countermeasure mapping lists.
  * Assign a risk ranking to the threats
  * Sort threats from the highest to the lowest risk, prioritizing the mitigation effort, such as by responding to such threats by applying the identified countermeasures.
    * Risk Mitigation Strategy might involve evaluating these threats from the business impact that they pose and reducing any found risk. 
    * Other options might include:
      * taking the risk
      * assuming the business impact is acceptable because of compensating controls
      * informing the user of the threat
      * removing the risk posed by the threat completely
      * or the least preferable option, do nothing.

##### Making of the Threat Model Documentation

Each of the above steps are documented as they are carried out. The resulting document will be the threat model for the application. 

Below will be a first draft of Resonate's Threat Model Document. Everthing here is added by Austin Howes (github username "austie702"), copied from private files of the Resonate (working title) project in his local directory for Resonate's preparation and creation. 