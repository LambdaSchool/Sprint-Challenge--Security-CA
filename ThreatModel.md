#Threat model

Francis is a successful local buisnessman who owns and operates three small hardware stores around the city. He conducts most of his bookkeeping from an office in the back of the founding location. The only people who have access to the records are francis himself and his longtime accountant Martha. The office locks and only keys belong to Francis, Martha and a maintenance person. Because a lot of local contractors frequents his stores, he runs an account system in which approved customers can charge purchases to a store account and be invoiced monthly. All the this data is stored on a local machine in the office. Francis said that the machine is password protected, but that since him and Martha both need access to it they chose a password that was 'easy for both of them to remember.'

#Attack Surfaces
In my estimation Francis's biggist vulnerability is the lack of a back up of his data. Not only does this make him vulnerable ransomware attacks, even a non malicious loss of data could be detrimentail to his buisness. The physical space is also a concern since there is a key holder who is not authorized to access sensitive data and also the strenth of the password protecting the machine.

#Adversaries
Francis could face threats from competing buisnesses, disgruntaled employees or even customers who might, for some reason, not want to pay their bill.

#Attack Vectors
Gaining access to the physical machine and cracking it's password would be the most obvious threat, but Francis could also be vulnerable to denial of service attacks or run of the mill tech failures.

 #Mitigations
 Francis and Martha need to have spereate accounts with seperate passwords and both need to be edjucated on choosing a propers passphrase. A password manager could be a good idea. I'm going to reccomend that the custodians key be revoked since that's a major attack vector and it's a small office that could be cleaned under supervision. This biggest improvment will be data backup, either through a secure cloud service or on a local raided server that is kept seperate from the office and under lock and key. I suspect that since the overhead is less and the sensitivity of the data is limited that a cloud back up service will do just fine.