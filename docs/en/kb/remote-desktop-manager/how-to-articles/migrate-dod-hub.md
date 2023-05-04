---
eleventyComputed:
  title: Migrate From {{ en.DOD }} to {{ en.HUBP }}
  description: To benefit from all the latest features, it is recommended to use {{ en.HUBP }} instead of {{ en.DOD }}.
---
To benefit from all the latest features, it is recommended to use {{ en.HUBP }} instead of {{ en.DOD }}.
{% snippet icon.badgeInfo %}
A [{{ en.HUBP }}](/hub/getting-started/create-hub/hub-personal/) needs to be created before migrating from {{ en.DOD }}.
{% endsnippet %}  

## Steps
1. Connect to the {{ en.DOD }} data source.
1. A prompt will appear about migrating to {{ en.HUBP }}, click ***Yes***.  
![Migration Prompt](/img/en/kb/KB0028.png)
1. Select the databases that should be migrated, then click ***Next***.  
![Databases](/img/en/kb/KB0029.png)
1. Enter the ***Master Key*** and click ***Open***.  
![Master Key](/img/en/kb/KB0030.png)
1. Once the files are done migrating, click ***Next***.  
![Migrating Files](/img/en/kb/KB0031.png)
1. A prompt will show files that were successful, skipped or had errors while migrating. Click ***Finish***.  
![Migration Report](/img/en/kb/KB0032.png)
1. The migrated files will now appear in the {{ en.HUBP }} data source.  
![Migrated Files](/img/en/kb/KB0033.png)