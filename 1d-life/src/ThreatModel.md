# Part - 1

Bob is a 58 year old independent CPA. He primarily services medium-income individuals and local businesses in his town of 10,000. Bob shares office space with two others, both also independent CPAs. He describes his relationship with them as cordial, but not quite friendly. They are in competition with one another after all.

These days, Bob does most of his work by computer. He regularly uses email, an online file sharing website, and desktop tax software in his work. Although he has had to learn many new things as his work has changed, Bob has gained a reasonable understanding of the technology he uses. The records for each of his clients are encrypted using a different password. He also used different passwords for each online service. These passwords are kept in a notebook, which Bob diligently keeps locked in his file cabinet when not in use.

## Adversaries

- Independant CPAs that work from the same office space as him. Also his customers adversaries could cause a problem if they find out that Bob is their CPA with access to all their personal data.

## Attack surface

- The face that he works out of an office with 2 other competing CPAs can be an issue. They probably also share the same network connection.

## Attack vectors

1.  Biggest threat is that notebook locked in a "file cabinet" that can be opened with a hammer or crow bar.
    - Recommendation -- secure all passwords in a reputable, well known, password manager. That leaves just one password you need to keep secure, the password for the password manager. Make it long, add punctuation and special characters. Even use a complete sentence to make it longer. The longer the better.
    - Lesser Solution -- If you prefer keepting them in a notebook, then secure the notebook in a more secure physical location. Heavy duty safe, bolted and hidden, in the office.
2.  Another possible threat is your network. All your network data is being sent throught a network that your competing CPAs use as well.
    - Recommendation -- Get your own modem and connection.
3.  Your computer. Are you using a laptop or a desktop? Do you leave it in the office? Anyone with physical access to your computer can install a backdoor/malware program for monitoring/keystrokes/etc.
    - Recommendation -- If using a laptop, dont leave it in your office.
    - Recommendation -- If using a desktop, make sure it is secured at all times. Secured in a locked desk, locked office. Dont have it displayed out in the open. Install Virus protection software to check for anthing that may have been loaded into you computer.

## Risks (Confidentiality, Integrity, Availability, etc)

- Banking information, social security numbers, birth cirtificates, and more highly confidential information for many clients. If a breech happens, all confidence in the CPA is lost, causing a siginifitant drop in clients.

## Types of Attacks (Man-in-the-middle, (Distributed) denial of service, Backdoors/malware, social, etc.)

- Man-in-the-middle -- Caused from possible unsecured and SHARED network connection.
- backdoors/malware -- Caused from possible unsecured computer physical location.
- old fashion password stealing -- Caused from all passwords being kept in an unsecured location.

## Mitigation - Included above in Attack vectors
