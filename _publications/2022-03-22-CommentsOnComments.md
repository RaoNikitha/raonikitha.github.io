---
title: "Comments on Comments: Where Code Review and Documentation Meet"
collection: publications
permalink: /publications/preprints/2020-10-19-CodeIntent
#excerpt: "The paper has been accepted for virtual presentation."
date: 2021-01-29
venue: 'Mining Software Repositories (MSR)'
year: '2022'
authors: '<b>Nikitha Rao</b>,Jason Tsay, Martin Hirzel, Vincent J. Hellendoorn'
arxiv: 'http://arxiv.org/abs/2204.00107'
#paperurl: ''
#bib: ''
---

A central function of code review is to increase understanding; helping reviewers understand a code change aids in knowledge transfer and finding bugs. Comments in code largely serve a similar purpose, helping future readers understand the program. It is thus natural to study what happens when these two forms of understanding collide. We ask: what documentation-related comments do reviewers make and how do they affect understanding of the contribution? We analyze ca.700K review comments on 2,000 (Java and Python) GitHub projects, and propose several filters to identify which comments are likely to be either in response to a change in documentation and/or call for such a change. We identify 65K such cases. We next develop a taxonomy of the reviewer intents behind such "comments on comments". We find that achieving a shared understanding of the code is key: reviewer comments most often focused on clarification, followed by pointing out issues to fix, such as typos and outdated comments. Curiously, clarifying comments were frequently suggested (often verbatim) by the reviewer, indicating a desire to persist their understanding acquired during code review. We conclude with a discussion of implications of our comments-on-comments dataset for research on improving code review, including the potential benefits for automating code review.

The paper has been accepted for presentation at [MSR 2022](https://2022.msrconf.org/){:target="_blank"}. 

> Collaborators - [Jason Tsay](https://researcher.watson.ibm.com/researcher/view.php?person=ibm-Jason.Tsay){:target="_blank"}, [Martin Hirzel](https://researcher.watson.ibm.com/researcher/view.php?person=us-hirzel){:target="_blank"}, [Vincent J. Hellendoorn](https://vhellendoorn.github.io){:target="_blank"}

Please find all the relevant resources below:
1. [Preprint on ArXiv.](http://arxiv.org/abs/2204.00107){:target="_blank"}
2. [Comments On Comments Dataset](https://github.com/microsoft/Search4Code/){:target="_blank"}

    