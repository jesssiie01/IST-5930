# Project 8 - Pentesting Live Targets

Time spent: 8 hours spent in total

> Objective: Identify vulnerabilities in three different versions of the Globitek website: blue, green, and red.

The six possible exploits are:

* Username Enumeration
* Insecure Direct Object Reference (IDOR)
* SQL Injection (SQLi)
* Cross-Site Scripting (XSS)
* Cross-Site Request Forgery (CSRF)
* Session Hijacking/Fixation

Each color is vulnerable to only 2 of the 6 possible exploits. First discover which color has the specific vulnerability, then write a short description of how to exploit it, and finally demonstrate it using screenshots compiled into a GIF.

## Blue

Vulnerability #1: SQL Injection

Description: Testing Blue vulnerability by typing in id=1%27 in the url. However, message of "database query failed" popped up. Therefore showed the SQL vulnerability exists in the blue.

![Animation](https://user-images.githubusercontent.com/89667680/140221356-a1eaa62f-a139-484a-b1cb-ac802095a6df.gif)

Vulnerability #2: __________________

Description:

<img src="blue-vuln2.gif">

## Green

Vulnerability #1:User Enumeration

Description: A username that does not exist, message pops up "log in was unsuccesful". However, message "log in was unsuccessful" will become bold when I use a user that already exist. 
![green-vuln1](https://user-images.githubusercontent.com/89667680/140232383-1fe3eacc-fa2f-4c67-ba30-3d2b6cbdc202.gif)

Vulnerability #2: __________________

Description:

<img src="green-vuln2.gif">


## Red

Vulnerability #1: Insecure Direct Object Reference

Description: I moditifed the url and inserted different ID numbers at the end, which can assist in gathering private information of the specificc salespersons. This shows the unsecured privacy that an attacked can receive. 

![red-vuln1](https://user-images.githubusercontent.com/89667680/140252764-17603b01-ed88-4de7-ba67-6a14900ab741.gif)


Vulnerability #2: __________________

Description:

<img src="red-vuln2.gif">


## Notes

Describe any challenges encountered while doing the work
