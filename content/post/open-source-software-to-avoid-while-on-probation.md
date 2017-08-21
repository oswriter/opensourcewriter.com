+++
date = "2017-08-21"
tags = ["Solus", "Luks", "California", "Ubuntu", "eCryptfs", "VeraCrypt", "zuluCrypt", "GPG", "Seahorse", "Encryptr"]
categories = ["Backups & Encryption"]
title = "Open Source Software to Avoid While on Probation"
+++

Strong encryption has always been a hallmark of Linux and the open source community in general. [Solus](https://solus-project.com), for example, offers full-disk encryption during the installation process using [LUKS](https://guardianproject.info/code/luks/). This means that once installed, LUKS requires a separate password at startup before decrypting and mounting the user's hard drive.

But what if you are legally prohibited from encrypting your hard drive? In some U.S. states, judges impose restrictions on the use of encryption as a condition of probation in criminal cases. This doesn't necessarily prevent someone from using the encryption features of certain programs, but there is some open source software that a user may need to avoid if he or she has been recently convicted of a serious crime.

### California Court Bans Drug Defendant From "Knowingly Using Data Encryption"

To give you an idea of how probation can affect a person's ability to use encryption and related software, consider this recent case from California. The defendant here entered a "no contest" plea to a number of felony and misdemeanor drug possession charges and was sentenced to probation. According to the original criminal complaint, a police officer found several Craigslist ads posted by the defendant that contained coded messages offering oxycondone for sale.

The trial judge imposed a number of conditions on the defendant's probation, including, "The defendant shall not knowingly possess or use any data encryption technique or programs." The defendant subsequently appealed this (and several other probation conditions) as "unconstitutionally overbroad" and "vague," since it arguably would prevent him from using *any* kind of encryption, including potentially visiting a website that uses the **https**  protocol.

The California Sixth District Court of Appeal, which is based in San José, rejected the defendant's arguments and upheld the probation conditions in an [August 16 opinion](https://scholar.google.com/scholar_case?case=11805788673341412315&hl=en&as_sdt=6,47):

	[We] disagree that the prohibition against the knowing use of data encryption would substantially infringe on [the defendant's] constitutional rights because e-mail accounts, electronic banking, cell phones, and many other electronic devices utilize some degree of encryption. The condition's scienter requirement serves to restrict its scope to the use of data encryption programs by [the defendant] to conceal his illegal activities, not to preclude him from checking his bank balance or medical test results online. The incidental data encryption employed when sending a text, e-mail, or accessing online portals for finances, health care and the like, is entirely different from knowingly using data encryption to forestall law enforcement from effectively searching an electronic device or digital media. As such, there is no constitutional overbreadth with regards to these probation conditions.

This was an "unpublished" decision, which means it is not considered binding legal precedent for future cases. So another California appeals court could conceivably interpret the scope of a similarly worded encryption ban more or less broadly. But the Sixth District's opinion offers a useful starting point for assessing what kinds of software might be covered by this type of probation condition.

### When "Plausible Deniability" Conflicts With Law Enforcement 

As noted above, Solus and many other Linux distributions use LUKS to provide full-disk encryption during the operating system installation process. [Ubuntu](https://ubuntu.com) and many of its derivatives also offer encryption of a user's home folder through [eCryptfs](http://ecryptfs.org/). Similarly, there are standalone programs like [VeraCrypt](https://www.veracrypt.fr/en/Home.html) that allow a user to create encrypted partitions and "virtual encrypted disks" within a file. VeraCrypt even enables the creation of "[hidden volumes](https://www.veracrypt.fr/en/Hidden%20Volume.html)" within an existing encrypted volume, which the developers claim provides "plausible deniability" in the event that "you are forced by someone to reveal the password to an encrypted volume." It's safe to say all of these programs would not be permitted under the Sixth District's ruling.

Here are some other programs I found, just in the Solus repository, that would also be problematic for a person under a probation-related encryption ban:

+ [zuluCrypt](https://mhogomchungu.github.io/zuluCrypt/), which encrypts hard drives and manages volumes encrypted by LUKS and other programs. 
+ [GNU Privacy Guard](https://gnupg.org/) (GPG), which allows for encryption of individual files through a number of front-ends, including a number of email programs.
+ [Seahorse](https://wiki.gnome.org/Apps/Seahorse), which manages passwords and encryption keys, and can be used to encrypt or decrypt individual files via an extension to the Nautilus file manager for the GNOME desktop.
+ [Encryptr](https://spideroak.com/encryptr/), an encrypted password manager published by SpiderOak.

### Encryption Bans Must Be "Reasonable"

It's important to reiterate that the restrictions on this particular defendant's use of encryption software was based on the specific facts surrounding his criminal act. As the Sixth District explained, while California trial judges have broad discretion in setting probation terms, a condition is "generally invalid" if it has "no relationship to the crime of which the offender was convicted." In this case, since the defendant "used an electronic device to arrange the sale of drugs he advertised on a Web site, it was reasonable for the trial court to give the probation officer the ability to ensure that [the defendant] was not violating his probation by arranging drug sales, by any means, on his electronic devices."