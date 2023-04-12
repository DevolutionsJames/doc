---
title: Domain Group Membership Is Not Retrieved Properly
description: This is a solution for when the domain group membership is not retrieved correctly from Active Directory.
keywords:
- Domain Group
- Domain Diagnostic
---

1. Access the {{ en.DPS }} web interface and connect using an administrator account.
1. Go to the ***Administration*** tab.
1. Go to the ***Server Settings – Authentification – Domains*** page.  
![Domains](/img/en/kb/KB0011.png)
*Domains*{.caption} 
1. Click on the ***Diagnostics*** button to the right of the correct domain.  
![Diagnostics Button](/img/en/kb/KB0012.png)
*Diagnostics Button*{.caption} 
1. Set the ***Diagnostic type*** option to ***Get groups by user***.  
![Get groups by user](/img/en/kb/KB0013.png)
*Get groups by user*{.caption} 
1. Enter a username from the problematic group in the ***Parameter*** field.
1. Set the ***Strategy*** option to ***Directory entry token group***. If this fails, instead use ***Directory entry token group (Legacy)*** or ***Recursively***.  
![Strategy](/img/en/kb/KB0014.png)
*Strategy*{.caption} 
1. Click on ***Get Diagnostic***.  
![Get Diagnostic Button](/img/en/kb/KB0015.png)
*Get Diagnostic Button*{.caption} 
1. Close this window by clicking on ***Close***.
1. Click on ***Edit***.  
![Edit](/img/en/kb/KB0016.png)
*Edit*{.caption} 
1. Click on ***Advanced Settings***.  
![Edit – Advanced Settings](/img/en/kb/KB0017.png)
*Edit – Advanced Settings*{.caption} 
1. Under ***Strategy***, change the ***Get groups by user*** option to the one selected in step 7.  
![Strategy – Get groups by user](/img/en/kb/KB0018.png)
*Strategy – Get groups by user*{.caption} 
1. Click on ***OK***, and then ***Update*** to save the changes.