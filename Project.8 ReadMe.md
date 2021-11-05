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


## Green

Vulnerability #1:User Enumeration

Description: A username that does not exist, message pops up "log in was unsuccesful". However, message "log in was unsuccessful" will become bold when I use a user that already exist. 
![green-vuln1](https://user-images.githubusercontent.com/89667680/140232383-1fe3eacc-fa2f-4c67-ba30-3d2b6cbdc202.gif)




## Red

Vulnerability #1: Insecure Direct Object Reference

Description: I moditifed the url and inserted different ID numbers at the end, which can assist in gathering private information of the specificc salespersons. This shows the unsecured privacy that an attacked can receive. 

![red-vuln1](https://user-images.githubusercontent.com/89667680/140252764-17603b01-ed88-4de7-ba67-6a14900ab741.gif)


Vulnerability #2: Cross-Site Request Forgery

Description: In this vulnerability the site takes in the post request, which if from a different source. However, the source is a hidden form and makes it accessable to the users database.

![red-vuln2](https://user-images.githubusercontent.com/89667680/140440405-151af406-3d7e-4fd5-8306-d8e32178cb3e.gif)



## Notes

The challenge I encourtered where being confused on how to do the cross-site request forgery. I received an error message on logging in, however was successful once I remebered the password. 
