---
title: Duo
---
{{ en.RDM }} for Mac allows you to configure a ***Duo*** authentication to provide an additional security layer when opening a data source. 

## Settings 

{% snippet icon.badgeInfo %} 
Before you start the configuration, make sure you have created a Duo account and have also installed the Duo application on your compatible device. 
{% endsnippet %}
 

1. In the Duo account, protect the Web SDK application.  
![Protect the Web SDK Application](https://webdevolutions.azureedge.net/docs/en/rdm/mac/RDMMac2058.png) 
1. If not already done, follow these [Multi-Factor Authentication Configuration steps](/rdm/mac/data-sources/multi-factor-authentication/) . 
1. After having selected the ***Duo*** MFA type, click ***Apply*** .  
![Apply Multi-Factor Configuration](https://webdevolutions.azureedge.net/docs/en/rdm/mac/clip10141.png) 
1. All the information necessary to fill in the ***Duo Settings*** fields in {{ en.RDM }} for Mac will be generated by the Duo account.  
![Duo Account – Web SDK Application Details](https://webdevolutions.azureedge.net/docs/en/rdm/mac/clip10142.png) 
1. Copy and paste all the information in the corresponding fields in the ***Duo Settings*** window.  
![Duo Settings](https://webdevolutions.azureedge.net/docs/en/rdm/mac/clip10143.png) 
1. Click on ***Check*** to validate the information, then click ***OK*** when done. 
1. If there is more than one device connected to the Duo account, click on ***Settings*** . If not, skip to <a href="#10">Step 10</a>..  
![Multi-Factor Configuration – Settings](https://webdevolutions.azureedge.net/docs/en/rdm/mac/RDMMac2059.png) 
1. Select the device to use for the multi-factor authentication by clicking on ***Use this device*** . 
1. Select the method by which to receive the Duo Passcode:  

    * Duo Push : The code is “pushed“ to the Duo application. 
    * Send SMS : The code is sent by SMS on the registered phone number. 
    * Phone : The code is sent by phone call; a computer generated voice will dictate the code. 
1. <a name="10"></a>Click ***Close*** when done.  
![Close the Multi-Factor Configuration Window](https://webdevolutions.azureedge.net/docs/en/rdm/mac/RDMMac2060.png) 

Once you have completed all the steps, you will be prompted with the Duo Authentication every time you connect to your secured data source. 

