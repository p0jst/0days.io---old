---
title: "Is CVSS the Right Measurement for Vulnerabilities?"
date: 2021-04-20T21:23:47+02:00
draft: false
---

## Is a number between 1 and 10 enough to rate and determine a vulnerabilities potential in your organization?

Common Vulnerabilitiy Scoring System (CVSS) is a ranking system that is being used as an industry standard for rating a vulnerabilties potential damage on your organization. The numerical score between 1 and 10 can then be translated into a qualitative representation, such as low, medium, high and critical to help organizations properly assess and prioritize the vulnerabilities found in their organization.
Usually the vulnerabilities are found by an automated tool from which within they are ranked based on the CVSS.
The main issue with CVSS is the way people tend to read the results. When we don't look any deeper into the results than the numbers, we become blind of what is really there.

Before first.org updates or puts a CVS score on a vulnerability, a lot of thought is put into it. How easily exploitable is it? How common is it? What's the potential gain? What system does it compromise? Not until all of those questions are asked (and a lot more) they can generate a number for that specific vulnerability.
If you do not ask yourself these very same questions each and every time you detect a vulnerability in your enviroment, you are potentialle exposing your enviroment unnecessarily.


## Is an automated vulnerability scanner the key for succes?