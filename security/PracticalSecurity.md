# Practical Security

In regards to this topic, I had already implemented some of these recommendations prior to this sprint challenge. For any account which supports it, I make use of two-factor authentication (though this often leads to being too lazy to log into something when the phone is across the room), and I also run a BSD virtual machine (BSD because it tends to be more secure than most Linux distributions, and typically has less malware concerns).

Changes I've implemented today include making use of KeePass, with a strong pass-phrase and a high number of iterations (saving/loading takes a while, naturally). I will also be setting up SSH and _possibly_ GPG in the next few hours, though these will need to wait as there's still the rest of this challenge to be completed.