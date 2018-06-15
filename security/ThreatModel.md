Dear <IT Administrator>,

Per our discussion I performed an internal security audit and discovered the following:

1) Company systems have an unacceptable rate of infection from malware, botnets, and viruses. (These include desktop, laptop, and mobile devices and of many brands.)

2) The greatest cause of such infections is from web browsers and unsafe users. Secondly issues seem to come from untrusted USB devices that have either been compromised and unintentionally distributed (e.g.- swag at expos and trade shows). Or by malicious means in which an attacker has physical access to a company device. (This can occur both internally and externally.)

In order to mitigate the first issue, I recommend we develop, test, and deploy a web browser that is a virtualized app so that it is containerized. The browser will have user uniqueness in order to allow for things such as bookmarks but the app itself will come from a secured read-only virtual image that is destroyed and re-created for every web "session". The virtualized web app will also be isolated from normal company traffic to mitigate internal infections.

To handle infections from untrusted devices, such as USB thumb drives, company devices need to have their USB ports restricted and at worse case completely disabled. The proper use of this will need to be further researched and tested before deployment.

If you have any questions please do not hesitate to ask.

Very Respectfully,

*Don*