---
inFeed: true
hasPage: true
inNav: false
inLanguage: null
keywords: []
description: I have a scary thought to share with you concerning the security of every cryptographic key used in the entire world.
datePublished: '2016-05-28T21:33:56.737Z'
dateModified: '2016-05-28T21:25:43.431Z'
title: Cryptographic Keys in Doubleplusungood Land
author: []
authors: []
publisher: null
starred: false
sourcePath: _posts/2016-05-28-cryptographic-keys-in-doubleplusungood-land.md
url: cryptographic-keys-in-doubleplusungood-land/index.html
_type: Article

---
![](https://the-grid-user-content.s3-us-west-2.amazonaws.com/87a1afcb-5334-4d50-95be-1a0d608870ef.jpg)

# Cryptographic Keys in Doubleplusungood Land

I have a scary thought to share with you concerning the security of every cryptographic key used in the entire world.

[A recent revelation][0] from the Edward Snowden treasure trove of secret National Security Agency documentation concerns the wholesale theft of [Gemalto][1] SIM card encryption key data that is used by cellular telephone carriers around the world. Every cell phone has a SIM card that uniquely identifies the phone and, as an afterthought, also holds keys used to encrypt the phone's transmissions, providing us with a modicum of privacy on our phone calls. If a third party has a copy of my SIM keys, then my phone call can be decoded and my privacy has been compromised.

Gemalto is an international Amsterdam-based company that produces a large percentage of the world's SIM cards. According to an April 2010 GCHQ document, "PCS Harvesting at Scale," hackers in the British GCHQ - NSA's Five Eyes European counterpart - decided it would be a jolly good show to infiltrate Gemalto's internal networks and intercept copies of the bulk shipment of SIM card key data being sent to the various phone carriers that Gemalto does business with. With a copy of billions of SIM card keys in its possession, the GCHQ and the NSA would have no problem decoding any phone conversation they captured that relied on a Gemalto SIM card for its privacy. Of course not only spy agencies could make use of cell phone encryption keys. Lots of money could potentially be made if you had access to the phone calls on Wall Street.

However, I'm curious about the possible confluence of this new SIM key revelation with the recent news concerning the [Equation Group malware][2], which at the moment is believed to be the most sophisticated cyber warfare product ever created, according to researchers from Moscow-based Kaspersky Lab. One of the capabilities of this malware is the ability to rewrite a computer hard drive's microcode, installing code that is difficult to detect or remove. Additionally, a proof of concept for rewriting the microcode on USB memory sticks to add invisible malware ([called BadUSB][3]) was demonstrated by researchers Karsten Nohl and Jakob Lell at the 2014 Black Hat security conference in Las Vegas. Clearly, rewriting microcode is 'the new black' for the elite hacking community.

So, riddle me this, Batman! While you're busy stealing the SIM keys, why not also take the opportunity to rewrite the microcode used on the company's cryptographic tokens? (This suggestion applies to all manufacturers' crypto cards and tokens). If you take a look at the Gemalto web site, they manufacture a lot more than just SIM cards, including a full range of cryptographic cards and tokens built to a high level of trust (FIPS & CC standards). Crypto cards and tokens are usually blank -- they have no keys on them -- when they are first shipped out to the customer. A customer will generate and store cryptographic keys on the tokens so they can be used for ePassports, eID, eHealth cards, etc., as well as to authenticate computer users, encrypt and decrypt email, and to digitally sign contracts and documents. In which case I'm sure the NSA Five Eyes group would love to have the ability to copy any encryption keys stored on a cryptographic token and push them to an NSA-controlled server. Wouldn't that be a coup?

All the tools, opportunity and motive for an even bigger computer crime may be in evidence here. I hope that Gemalto (and every other cryptographic token manufacturer) is performing forensics not only on their SIM card business but also, more importantly, their cryptographic token manufacturing and distribution processes. However, I'm wondering if we even have the forensic tools to find such malware if it was really well hidden inside our supposedly trusted cryptographic products.

I know it sounds a bit paranoid, but it's possible that in order to do its job the NSA has its sights on nothing less than possession of every cryptographic key used in the entire world. If this turns out to be the case, then we really are in _doubleplusungood\*_ territory.

\* A term that originated in [Newspeak][4], a fictional language coined in [_Nineteen Eighty-Four_][5], a 1949 dystopian novel by George Orwell.

[0]: https://firstlook.org/theintercept/2015/02/19/great-sim-heist/
[1]: http://www.gemalto.com/
[2]: http://arstechnica.com/security/2015/02/how-omnipotent-hackers-tied-to-the-nsa-hid-for-14-years-and-were-found-at-last/
[3]: http://www.wired.com/2014/07/usb-security/
[4]: https://en.wikipedia.org/wiki/Newspeak
[5]: https://en.wikipedia.org/wiki/Nineteen_Eighty-Four