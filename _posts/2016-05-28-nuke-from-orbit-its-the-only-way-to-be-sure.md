---
inFeed: true
hasPage: true
inNav: false
inLanguage: null
keywords: []
description: '“There are just two types of companies: those that have been hacked, and those that will be. Even that is merging into one category: those that have been hacked and will be again” says Robert Mueller, FBI Director. '
datePublished: '2016-05-28T21:33:57.058Z'
dateModified: '2016-05-28T21:29:53.965Z'
title: 'Nuke From Orbit: “it’s the only way to be sure”'
author: []
authors: []
publisher: null
starred: false
sourcePath: _posts/2016-05-28-nuke-from-orbit-its-the-only-way-to-be-sure.md
url: nuke-from-orbit-its-the-only-way-to-be-sure/index.html
_type: Article

---
![](https://the-grid-user-content.s3-us-west-2.amazonaws.com/c51befd8-6daf-4a45-b45f-b2595734a3ef.jpg)

# Nuke From Orbit: "it's the only way to be sure"

_"There are just two types of companies: those that have been hacked, and those that will be. Even that is merging into one category: those that have been hacked and will be again" says Robert Mueller, FBI Director. _

If we are _always_ going to be several steps behind the computer hackers who eventually find the means to engineer their way into our protected networks and systems, what then should we do? We need an imaginative and proactive stance to help minimize the risk of data loss if or when we get hacked. I have a wacky idea to share with the IT Security community, and I'd like your feedback please.

Having [_situation awareness_][0] is a good start, and robust [_defence in depth_][1] goes a long way to handling all the normal threats and vulnerabilities that are encountered in our regular day-to-day security work. But what about handling the exceptional cases like the actions of disgruntled insiders and APT malware? Often what seems to happen is the intruders have long since copied the data they want and have exfiltrated it before the SOC even has a chance react to the data theft.

Now, this may sound a bit over the top but please bear with me for a moment. What if we added some 'extra special files' with enticing names like Bank\_Accounts\_Excel\_Bkup.zip to our important enterprise file systems and placed them in close proximity to the sensitive and valuable data we're trying to protect. These files are never meant to be opened, so we can add a simple password to stop the merely curious/blundering idiots from opening them. However, when the file is cracked, the unzipped payload automatically executes a low level format on all attached media. Probably not what the hackers were expecting to find inside our Excel bank accounts spreadsheet, right? By using an offensive Trojan horse, we at least have the potential to erase our stolen company data as well as cripple the hackers who took it.

Are we sinking to the same murky depths as the hackers we are fighting? Absolutely. As an IT security professional, is this an ethically acceptable action to take? Probably not. But we do have the right to protect our data; in fact, it's our mandate to protect our corporate data.

There may be some technical issues building such a Trojan horse. What if it ends up running in a virtual machine, rather than a simple Windows OS? Can we build something universal that will also run in a Linux and OS/X environment? What's the best autorun agent? Does the payload have to be encrypted to escape the hackers' own malware detection? Given the sophistication of the recently documented Wipall and Destover malware components that did low level disk destruction at Sony Pictures, it's probably safe to say these are technical issues that have already been solved.

There are other options too: one could encrypt the media it was launched on, or perhaps even look for metadata characteristics associated with your company's files and just delete those files. However, this would not be as effective in ensuring the proper destruction of sensitive data or deterring the hackers from coming back for more. Booby-trapping your own company's file system with a low-level formatter so the intruders erase their own system when they try to open the stolen files seems like a much stronger deterrent.

Until we have a perfect metadata classification system for all of our valuable company data and an automated means of stopping its migration from the expected zones where it normally resides, we are left with only one other option: find a way to destroy what has been taken. Remember Ripley's famous words from the movie _Aliens_: "nuke the entire site from orbit. It's the only way to be sure."

[0]: https://www.linkedin.com/pulse/situation-awareness-cyber-security-defence-walter-cooke-cissp
[1]: https://www.linkedin.com/pulse/reign-bastion-castle-ending-walter-cooke-cissp