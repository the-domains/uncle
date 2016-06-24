---
inFeed: true
hasPage: true
inNav: false
inLanguage: null
keywords: []
description: >-
  My last cyber security post introduced the concept of Situation Awareness –
  having your finger on the pulse of your computer network and knowing whether
  you’re having a ‘good day’ or a ‘bad day.’ Hopefully your organization’s IT
  security posture promotes this concept and uses it to help stay one step ahead
  of the recent computer hacking headlines we’ve all been reading.
datePublished: '2016-06-24T20:31:53.588Z'
dateModified: '2016-06-24T20:19:15.592Z'
title: Situation Awareness & Cyber Security Defence
author: []
sourcePath: _posts/2016-05-28-situation-awareness-and-cyber-security-defence.md
authors: []
publisher: null
starred: false
url: situation-awareness-and-cyber-security-defence/index.html
_type: Article

---
![](https://the-grid-user-content.s3-us-west-2.amazonaws.com/c9b89d25-e406-4533-9e99-6208d0242e81.jpg)

# Situation Awareness & Cyber Security Defence

My last cyber security post introduced the concept of _Situation Awareness_ -- having your finger on the pulse of your computer network and knowing whether you're having a 'good day' or a 'bad day.' Hopefully your organization's IT security posture promotes this concept and uses it to help stay one step ahead of the recent computer hacking headlines we've all been reading.

Nobody wants their company's IT security failure to be the headlined subject of tomorrow's paper. And it seems that 2015 is already off to a bad start. Security researchers are predicting that 2015 will be "the year of the healthcare breach." The recent access of perhaps more than 80 million client records at Anthem Health - the second-largest health insurer in the United States - would seem to mark that prediction as correct. The information accessed includes customer names, birthdays, medical IDs, social security numbers, street addresses, e-mail addresses and employment information, including income data. While the damage assessment is ongoing, Anthem said there is no evidence at this time that credit card or medical information was compromised. However, we should not simply shrug our shoulders at this latest in a long line of IT security bad news stories and just carry on as normal.

In the interest of helping your IT Department (and upper management) sleep better at night, here are some free and cheap things you can do to reinforce your Situation Awareness security profile. 'Free' as in doesn't require capital outlay for hardware and software, and 'cheap' as in it won't take a lot of your IT department's precious resources away from other pressing matters. Also, it allows you to reuse any old servers you were planning on tossing into the company's dumpster. Recycle them instead and feel better for not adding them to the planet's already overflowing garbage dumps!

Let's look at two security vulnerabilities we would like to address: the external hacker and the internal disgruntled employee. Both decide they want to exploit a weakness in your existing systems and extract some valuable information assets and/or destroy your systems on their way out the door. How do we deter them or catch them in the act? Suggestions I offer to clients include _NIDS, honeypots_ and _tar pits_. These security services can run on any old PC or server you have laying around, and use free Linux OS and Open Source tools to do their Situation Awareness security work. There are lots of web-based resources and network security books available to help you implement these security tools.

A Network Intrusion Detection System (NIDS) is a server that passively examines all of the company's network traffic as it streams past, looking for the signatures of malware, viruses and other indications that someone is actively probing your network, looking for computers to attack and weaknesses to exploit. Most organizations position their NIDS at the boundary of their network, either as a part of their firewall infrastructure or in front of vulnerable web servers and other networked systems. However, if malware, hackers or a disgruntled employee are potentially inside your network, why not also have a NIDS server scanning your internal network traffic for signs of trouble? The most commonly used Open Source NIDS application is called _Snort_, and it is a part of a full suite of free tools that can be leveraged to alert you to both internal and external attacks.

A honeypot is a server that is set up to look like a working system that contains interesting or valuable company data. Open and inviting, it waits for your overly curious employee or intruder to access its services and try to break in. Because it has no real business function, any access by anyone is, by definition, a security flag that should be investigated. Interestingly, a properly constructed honeypot will help alert you to both internal threats and external threats that have managed to infiltrate your network and become internal threats.

A tar pit is a security-hardened server that usually sits on the outside Internet boundary of your network (outside your firewall). It acts as a sticky weapon to stop outside hackers from gaining information about your network. A hacker who accesses a tar pit to determine what services are available finds his own computer stuck and unable to pull any information at all from your network. A working tar pit server will often have hundreds of thousands of stuck connections from outside hackers who are attempting to scan a network for vulnerable systems!

Adding these additional safeguards to your infrastructure can also help you pass your next audit. The evidence that you have these security controls in place and are actively reviewing the output from them will help fulfil compliance checks for appropriate network security controls and security monitoring activities.

Finally, many IT shops have already invested money in applications to help manage their infrastructure and alert staff when things have gone casters-up -- think of utilities like _Tripwire_, _WhatsUpGold_ and other similar products. Sometimes staff have just never bothered to fully deploy a tool because they got it for one thing but never thought of what other uses it might have. You should leverage every IT monitoring and reporting resource that has already been deployed to help improve your Situation Awareness.

Good luck! And if this still looks too difficult to pull together on your own or you need it yesterday, then please contact me and I will hook you up with some resources that can help you "keep calm and git 'er done!"