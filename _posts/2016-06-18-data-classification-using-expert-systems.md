---
inFeed: true
hasPage: true
inNav: false
inLanguage: null
keywords: []
description: Data Classification using Expert Systems
datePublished: '2016-06-26T21:26:12.195Z'
dateModified: '2016-06-26T21:25:42.529Z'
title: ''
author: []
sourcePath: _posts/2016-06-18-data-classification-using-expert-systems.md
authors: []
publisher: null
starred: false
url: data-classification-using-expert-systems/index.html
_type: Article

---
![](https://the-grid-user-content.s3-us-west-2.amazonaws.com/d4ccfa6f-8961-4fb6-a30e-eceaaa31ea71.jpg)

**Data Classification using Expert Systems**

Classifying data according to its sensitivity and value is part of the due reasonable care that should be practiced in every organization in their Data Governance process. This work is usually done manually, but time and resources may be saved by automating the entire data classification process. Automation may use any of the Expert System software packages that run on ordinary personal computers. 

This paper describes the work involved in creating and moving from a manual, questionnaire-based classification process to an automated process using Expert System software. The benefits of using an "expert on a disk" include tangible cost savings and the ability to logistically manage and compete a job which would otherwise bury a team of analysts in paperwork.

Copyright (c) Walter J. Cooke, 1994, 2016\. All rights reserved.

**An Expert on a Disk**

Like the cobbler whose children have no shoes, Information Technology (IT) departments who are tasked with automating their organization's work often get around to automating their own work last. IT is the department most often charged with data security custodial responsibilities. IT security analysts spend their time maintaining access rules, architecting security for new application systems, developing and enforcing security policy. Classifying data according to its sensitivity and value is another part of the Data Governance security work that should also be done. Unfortunately, this work is often not done or is only partly completed due to the time and resources needed to perform the job correctly. This work is usually done manually, but automation is possible using the Expert System software packages that run on ordinary personal computers.

An Expert System (ES) emulates deductive reasoning. It uses a symbolic representation of knowledge concerning a bounded, well-defined area of interest, such as selecting the proper chemicals for an experiment, or leading a consultant through a set of tests to decide what components are required to properly configure a new computer system. This knowledge is usually coded in the ES as a set of rules which define the action to be taken if the knowledge being tested during a consultation is true or false. Baysian analysis can also be used to determine if an state is unknown, more likely, or less likely to be true. The rules are constructed by a domain expert who use their experience of the area to define a set of elements that, when evaluated together, can lead the user to a proper conclusion, just as if the experts were personally questioning the user. For this reason, Expert Systems are often viewed as an "expert-on-a-disk." The set of rules in the Expert System form the model of the domain under consideration. If a process leading to a decision can be modelled, then the process is a suitable candidate for modelling as an Expert System. The process of reviewing data attributes and other domain information to decide how information should be classified according to its confidentiality, integrity, and availability components can be modelled in this way.

**THE VALUE OF DATA**

Today, corporate and departmental assets are more often stored in a computer system than in a locked safe. Information, being a valuable asset, must also be protected. Before allocating resources to protect data, we must first decide what information is of value, and how valuable it is. Data classification is usually done as part of Data Governance or Information Resource Management (IRM) planning for the enterprise. Lists of information repositories such as printed reports, databases, and sensitive documentation are assembled and evaluated for their value and sensitivity. Value can be measured in terms of actual dollars, competitive advantage, or corporate operational or regulatory requirements. Sensitivity can be measured in terms of technological trade secrecy, such as a drug formula, or as embarrassment to the organization were the information to become generally known. Information subject to legal or government regulations and employee and shareholder information also have a value and sensitivity component which generally requires that confidentiality be maintained. However, you cannot hold someone accountable for the protection of sensitive assets if they don't know how sensitive the asset is. This situation can have legal implications for an organization. Once a sensitivity value is determined for a piece of data or an entire database, the data can then be labeled with this value and given the appropriate level of safeguarding to protect it.

The cost associated with evaluating and classifying organizational data can be large because of the time and resources needed: roughly $16,000 per thousand corporate data items. A loose rule-of-thumb is that no more than 30% of the enterprise's information should require classification. In most environments the remaining 70% should not be of sufficient sensitivity to require classification. There are, of course, exceptions such as the military, and primary R&D establishments such as pharmaceutical companies. However, this rule is often forgotten by over-exuberant classifiers who either feel their data is never important to anyone but themselves, or by classifiers who use the Delphi technique and through lack of expertise end up over-classifying their data. Aside from the problem of classifying too much data, there may be problems with too many data classifiers. Using a team of classifiers to save time may result in varying standards being applied. With one classifier or many, though, even the sensitive 30% of an organization's information can prove to be an overwhelming amount of work to sort through and correctly classify. For these reasons, a means of automating this work is highly desirable, and Expert Systems provide a way to do this.

**DATA CLASSIFICATION SCHEMES**

Information classifiers in government and the military have an easier classification job because very precise classification criteria and values have been carefully defined and documented. However, industry has no such rules to go by, and many industries and organizations require their own unique classification system to properly evaluate their information assets. A number of distinct types of organizations can be distinguished by the kinds of information each one handles. Research has determined that there are at least six kinds of organizations with differences in information types significant enough to warrant their own category. These organizational categories are: Government, Military, Corporation, University, Health, and Primary Research & Development. Naturally, the classification system that would apply to a large financial institution would not be appropriate for a pharmaceutical research and development institution. For example, a financial business might require labels for Unclassified, Proprietary, and Company Restricted data. But the pharmaceutical business might additionally use some equivalent of Secret labeling for very sensitive formulas and trade secrets. Because these separate organizational categories exist, any manual or automated classification process should draw the user's attention to the fact that the process should only be used in the organization for which it was specifically designed. Automated classification systems can contain checks to ensure that this rule is observed.

The usual method for performing data classification involves designing a questionnaire that uses a series of questions to probe all enterprise, department, and data owner issues that are pertinent to the value or sensitivity of the enterprise's information. Typically the questions will be in four sections: confidentiality-disclosure, integrity-modification, availability-destruction, and control questions to ensure correctness and consistency in user responses.

The types of typical questions from each section might be as follows:

A) confidentiality-disclosure:

"If the data were disclosed to the public or appeared in the media, could it result in embarrassment to the organization, loss of image/reputation, or negatively influence public opinion?"

"Would a competitor would find this information valuable, and would our position in the market be damaged if it were released?"

"The data was collected from our customers, employees, shareholders, bondholders, or others, with the implied assumption that it would be used for a specific purpose and be treated as confidential in all other cases?"

"Would divulging this information compromise our security in other ways? For example, the release of computer passwords, key system manuals, security operating procedures, etc."

B) integrity-modification:

"Errors, omissions, or unauthorized modifications in this information could perpetrate a loss to the organization of how much money on an annual basis? For example: $1,000, $50,000, $100,000."

"The highest allowable error/omission rate for this data is:"

C) availability-destruction:

"The approximate dollar cost of recreating the data or information if it were to be completely destroyed or lost would be:"

"If the data were completely destroyed, the approximate time needed to recreate it would be:"

"The data being unavailable for one month would cost the organization losses of:"

"Is this document a negotiable instrument, such as a cheque?"

"Is this form used to initiate financial transactions, or is it a key operating document such as a purchase order, cheque requisition, etc.?"

A proper classification scheme requires a domain expert to devise a weighted counting scheme that sets a series of thresholds, from the least sensitive category of data up to the highest category of data. Over-ride situations must also be taken into account. For example, if there is a document category known to be very sensitive because it can easily be sold to a competitor, such as drug formulas or customer lists, then the classification scheme might automatically want to assign a minimum score to the document, regardless of what the evaluator scoring the document might indicate. For example, your questionnaire might tell the user that "if a report has a confidential component and a score of 31 or more for questions one through eight, it shall be classified as Company Restricted regardless of what the total score of the questionnaire is found to be." The need to add complex overrides, or account for situations where the dollar value of the asset is more important than the sensitivity of the asset, all make the scoring process more complex than completing your last income tax return.

In an ideal world, the evaluation process allows the classification expert to sit down with the owner of the information being reviewed. The classification expert explains the questions and possible responses to the data owner. The classification expert then takes the client's responses and, using a previously developed scoring system with weighted questions and sections, adds up the scores for each question in each section. The final total is compared to a predefined scale: for example scores from zero to forty mean the information is to remain unclassified; from forty-one to eighty means it is confidential, and anything greater than eighty is restricted. The trick of successfully designing the scale and weighting factors lies in two areas: working through enough examples manually to determine the lower and upper boundaries of each classification category, and viewing the information from an enterprise level so that you have a feel for the range of information subject areas and their relative sensitivity levels. Once the value and sensitivity of an asset is determined, its meta-data (and its storage or data medium) can be labelled with its classification.

Because the classification expert never has the time to sit down with the owner of the information being reviewed, most organizations train managers and data owners to do the classification process on their own. However, the correctness of manual classification schemes can be compromised by using poorly taught, ill-equipped classifiers. In a more realistic scenario, an email memo arrives telling you that company policy now requires that all important information in every department be evaluated using the attached questionnaire. Good luck, and don't forget to complete it by the deadline. The first problem is hunting down the hundreds of important computer files and databases you may own, plus all the management reports you regularly generate. Also, explanations are seldom provided on how to interpret the questions, nor are extra bodies supplied to fill out a questionnaire for each report and database. Poorly designed questionnaires lacking a definition of terms used and an explanation as to why a question is being asked will result in poor classification results. The work ends up getting done incorrectly, incompletely, and late.

An example from a real life situation may describe the folly of a paper-based data classification process. Initially the management at Consolidated Widgets Inc. assumed (optimistically) that a questionnaire could be used to collect and score the data that would provide a sensitivity rating for all the information under scrutiny. With a bit of training, they thought, it would only take five minutes to fill out the questionnaire, calculate the scores, and interpret the results to come up with the final sensitivity rating (Public, Company Confidential, Company Restricted). However, after one unfortunate episode where dozens of managers were trained to collect, quantify, evaluate, and finally classify the data under their control using the manual questionnaire technique, several things became crystal clear. First, managers were ill-equipped to deal with the volume of background information they needed to assimilate in order to do the classification work. Secondly, the managers could not afford to spend the time required to correctly answer the manual questionnaires and calculate the scores for all of the relevant pieces of information. Finally, questionnaire scoring fatigue quickly set in and few of the managers wanted to complete the work. Some managers delegated the work to untrained subordinates which reduced the accuracy of the scores. The result was that the manual questionnaires were poorly scored or not completed due to time and effort requirements. Those of us managing the classification work quickly lost logistical control of the project as we were buried under an avalanche of paper and could not determine the completeness of the work for each company department. To address these problems with the manual method, we constructed an Expert System by modelling the questions, rules, and scoring work from the manual questionnaire.

**MOVING TO AN EXPERT SYSTEM**

The effort to build a data security classification program is the same for both manual and Expert System processes until the time comes to deploy the process into the departments who will actually carry out the work. The paper-based system then becomes logistically difficult (even impossible) to manage. In comparison, the Expert System can be web-based, pushed out by GPO, or made available on a central file share as a run-time system and attached rule base that can be used on any standard Personal Computer. No paper documentation is required, as an integrated help system can lead the user through the scoring process and give detailed explanations about the meaning of each question which is asked. The classification score is automatically calculated, weightings added, over-ride situations factored in, and the final dollar value and Unclassified, Confidential, or Restricted label displayed on the screen. The user can run the Expert System as many times as needed to classify all of the sensitive information being reviewed. It is estimated that the cost ratio is approximately 12:1 for paper-based to Expert System-based data classification systems. This reflects both the questionnaire completion time savings (34 work days Vs about six work days per thousand data items) and the associated savings in less visible areas such as training, project management time, help desk support, accuracy audits, and paper savings.

Every successful Expert System-based data security classification system must start with a correctly working, paper-based questionnaire. Once a questionnaire is designed and tested, this information can be directly transferred into an Expert System software tool's rule base. The selection of an ES tool will be based on your need to manage cost, complexity, or need to work on multiple computing platforms. Some older commercial tools such as VP Expert, EXSYS, and AION cover the full spectrum of price and features, with VP Expert at the low end and AION at the high end. The price of ES software bears some relation to the learning curve experienced when starting to use the tool. A number of free Open Source ES tools are also available (Drools, CLIPS, Pyke, Jess, etc.), as long as you are willing to roll up your sleeves and learn a bit more of the basic programming processes. An alternative to ES software is a traditional development language such as Python, or a database application. However, ES software is better at managing the user interface, computation, and knowledge-based data used to drive the ES reasoning. Also, most ES packages are written in C or Python, and the speed of the software is not a problem in any but the largest of models with thousands of rules.

The most time-intensive task encountered when translating a paper-based questionnaire into a rule-based ES is the need to modify the syntax and format of all the questions. The language used to phrase the question is important because it determines both the size and content of the attribute lists in the knowledge base. You have to rewrite your questions into the form expected by the ES software, and group the attribute lists in an orthogonal format. If possible, it is beneficial to determine the ES tool you intend to use _before_ you write the questions for your paper-based questionnaire. Determining the syntax and format which the ES tool expects the questions to appear in can then guide you in constructing the manual questionnaire. Fewer format changes will then be needed when it comes time to port the model into the Expert System.

For example, you may have originally written out the paper-based questionnaire with a question like: "Rate the level of significance this data has according to the following four categories: 1) of Corporate significance; 2) of significance to a group within the Company; 3) of significance to an individual; 4) of significance to no one." However, the format expected by the Expert System may require that all of the possible choices be listed at the end of the question, and so it would have to be reformatted to read:

"The data or information being reviewed is of significance to:

CHOICES information: Enterprise, Group, Individual, No one."

When the Expert System rule base operates, the individual rules can fire in any order, depending upon what conditions are true and what kinds of actions can occur. Testing all the combinations of possible actions and results can be time-consuming, but a complete test plan is absolutely necessary. If you incorrectly spell the name of a data entity when coding a rule, or if the rule is inserted in the wrong order, it may not "fire" at the proper time to ask the appropriate question.

Control questions in the rule base serve several purposes. First, they provide a "sanity check" to ensure that the classifier isn't playing "monkey-at-the-keyboard." Second, control questions can prompt the classifier to check for special situations where additional research is needed before answering a question. For example, an evaluator may not recognize that if a report contains varying amounts of sensitive information, then the entire report should be classified at the level of its most sensitive information. Finally, control questions allow the rule base to flag unusual situations for follow-up by the domain expert. If the ES encounters a situation outside of its knowledge domain, then it can attempt to collect data on this new situation. For example, in one ES classification experiment, a classifier contacted the domain expert to report that the system wouldn't work on some important items. The domain expert discovered that the user was trying to classify recorded video files, which we had never given any thought to as a possible source of information that might require sensitive labeling and handling. A more robust model might have included input allowing the user to update the rule base with new information concerning the kind of data they were attempting to evaluate. In this respect Expert Systems can, in a limited sense, "learn" from experience.

**THE BENEFITS OF USING EXPERT SYSTEMS**

The benefits of doing the data classification work by using an Expert System are:

* much less paper work: a file containing the rule base and run-time system is distributed with simple instructions to use the ES;
* cost savings, both tangible and intangible, mostly associated with time reduction;
* anyone can use it on a standard PC; there are no special hardware requirements;
* a storage and sharing of esoteric knowledge: the ES hosts knowledge that won't be lost if the domain expert retires or leaves the organization;
* the ES can provide help, and explain how and why it reached its result;
* improved speed, accuracy, and consistently repeatable correctness of results;
* very complex confidence factors, weighting and override schemes can be designed into the ES;
* ES tools can handle "I Don't Know" and "Possibly" responses by using Bayes theorem;
* many ES tools can directly import information from Excel and other databases to ease the work of constructing the rule base;
* the ES rule base can be easily updated when the model needs changes or additions;
* the ES can modify and add to the knowledge base during a consultation when new information is encountered, so in a limited sense the ES is able to "learn" from experience;
* usually the users have no preconceived notion of how the work should be done and no resistance to do it, since it is straight-forward, fast, and the machine performs all the calculations using the minimum number of questions required to reach a conclusion;
* there is a much higher probability that the data classification work is completed.

It is also possible to move your model from one Expert System to a different Expert System package. You might want to do this if your model outgrows the features available in your current package, or because you decide to make the Expert System available for consultation over a network. Experience has shown that about two weeks of work are required to re-program the ES in a new syntax, and another one to two weeks is needed to properly test the new model, iron out unexpected bugs and misunderstanding on how the new software works, add help screens, and document the correct operation and usage of the new system.

As a final inducement to use Expert Systems, over-worked Security Department staff might consider all of the interesting job tasks that they would prefer to be doing. Rather than remaining buried under hundreds of questionnaires and listening to telephone calls requesting help, there will be time to do the work that only a professional Security Analyst can do. Meanwhile, your expert-on-a-disk will be looking after some of the mundane parts of your INFOSEC work.

_This paper was originally presented at the Sixth Annual Canadian Computer Security Symposium in Ottawa, Canada, in May, 1994\._

For more information contact: Walter Cooke, CISM, CISSP

cooke ( at ) uncle (.) com

Archived at: http://uncle.com

**Version 1.6 last updated June 10, 2016\. All contents copyright (c) 1996, 2016, General Intention. All rights reserved.**