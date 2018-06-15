As a software developer, the number one safety measure that I am implementing in my life style is encryption using a third party password manager. I already have an SSH key setup in my Github that I will be implementing from here on out so I can be accustomed to protecting my data. Since I am a Linux user (which I love), there are some pretty good software and manageability in place that helps encrypts and protects the data on your operating system from being compromised. Kali Linux was made specificatlly for security manageability for Linux. Unfortunately, I didn't chose Kali...YET! 

I chose the GPG Key Pair because it was something just to test and see what it is all about. This method is strictly ran through the commandline which I am striving to master (I am pretty close...). The steps are pretty straight forward so I am including what I did and a minor setback that has happened in this process. Here is my calculated steps:

1. Type in the commandline: gpg --full-generate-key
2. Please select what kind of key you want:
   (1) RSA and RSA (default)
   (2) DSA and Elgamal
   (3) DSA (sign only)
   (4) RSA (sign only)
* I chose the first option
3. RSA keys may be between 1024 and 4096 bits long. What keysize do you want? (3072)
* I chose the default number of 3072
4. Please specify how long the key should be valid.
      0 = key does not expire
      <n>  = key expires in n days
      <n>w = key expires in n weeks
      <n>m = key expires in n months
      <n>y = key expires in n years
* I gave an expiration date of 1 day just to test it out

Below is the information that will be listed in the terminal:

Real name: 
Email address: 
Comment: 
You selected this USER-ID:
    "Real name (comment) <email@email.com>"

Change (N)ame, (C)omment, (E)mail or (O)kay/(Q)uit? o

This happened because I writing out my password(which I didn't need to do) and took too long typing out the passphrase on the screen: 

We need to generate a lot of random bytes. It is a good idea to perform
some other action (type on the keyboard, move the mouse, utilize the
disks) during the prime generation; this gives the random number
generator a better chance to gain enough entropy.
gpg: agent_genkey failed: Timeout
Key generation failed: Timeout

I did the previous steps over and this is how it looks at the end: 

Change (N)ame, (C)omment, (E)mail or (O)kay/(Q)uit? O
We need to generate a lot of random bytes. It is a good idea to perform
some other action (type on the keyboard, move the mouse, utilize the
disks) during the prime generation; this gives the random number
generator a better chance to gain enough entropy.
We need to generate a lot of random bytes. It is a good idea to perform
some other action (type on the keyboard, move the mouse, utilize the
disks) during the prime generation; this gives the random number
generator a better chance to gain enough entropy.

gpg: key *************** marked as ultimately trusted
gpg: directory created
gpg: revocation certificate stored as *******************
public and secret key created and signed.

pub   rsa**** 2018-06-15 [SC] [expires: 2018-06-16]
      ********************************************************
uid                      name (comment) <email@email.com>
sub   rsa**** 2018-06-15 [E] [expires: 2018-06-16]

You can now use your GPG Key but once it expires, you have to create a new one. I really like the fact that you can have an expiration that you are in control of set. I also like that you can use the terminal to set the process and also get better at working in the terminal.
