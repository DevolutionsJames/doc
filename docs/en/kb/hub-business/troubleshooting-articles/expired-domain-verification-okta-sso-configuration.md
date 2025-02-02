---
eleventyComputed:
  title: Expired domain verification in Okta SSO configuration
  description: When configuring single sign-on (SSO) with Okta in your {{ en.HUBB }}, the first step is to verify your domain. This validation lasts for 48 hours and does not restart after that period. If you do not configure your TXT record within those 48 hours, your validation status will be expired and you will be stuck.
---
When configuring single sign-on (SSO) with Okta in your {{ en.HUBB }}, the first step is to ***Verify your domain***. This validation lasts for 48 hours and does not restart after that period. If you do not configure your TXT record within those 48 hours, your validation status will be ***Expired*** and you will be stuck.

Follow these steps for a workaround:

1. In {{ en.HUBB }}, go to ***Administration – Authentication – Single Sign-On (SSO)*** and select ***Okta Single Sign-On (SSO)***.
1. In the first configuration step, change the ***Domain*** name, then click ***Continue***.
![Changed domain name](https://webdevolutions.azureedge.net/docs/en/kb/KB2243.png)

1. Next, follow the complete verification steps **without** changing the TXT record (click ***Next*** and ignore the data).
![Verification steps](https://webdevolutions.azureedge.net/docs/en/kb/KB2244.png)

1. Go back to your Okta configuration page.
1. In the first configuration step, change the ***Domain*** name to the correct one, then click ***Continue***.
![Correct domain name](https://webdevolutions.azureedge.net/docs/en/kb/KB2245.png)

1. Follow the complete verification steps again, but this time enter the correct parameters in the TXT record since they have now changed.
![Verification steps with the correct parameters](https://webdevolutions.azureedge.net/docs/en/kb/KB2246.png)  

Your configuration should now be working.
