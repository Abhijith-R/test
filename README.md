[![published](https://static.production.devnetcloud.com/codeexchange/assets/images/devnet-published.svg)](https://developer.cisco.com/codeexchange/github/repo/Abhijith-R/SDWAN_Data_Prefix_Nslookup)

# Automation of Data Prefix List updation on vManage
New prefixes are added to a domain time to time. This script intends to automate the querying for new prefixes related to a domain and update the same to the data prefix list on vManage without human intervention.

#### Author:

* Abhijith R (abhr@cisco.com)
*  Apr/May 2019
***

#### Prerequisites
* Python 2.7/3.0
* PyCharm/Any text editor
* Flask

### Steps to Reproduce
* Download/clone the repository
* Make sure you make changes in the nslookup_google.py inside scripts folder with a valid vManage IP
* Modify the domain name as required in the code.
* Execute using a text editor such as pycharm
* Terminal can also be used to run the code.
      ```python nslookup_google.py```

#### API Reference/Documentation:
* [vManage REST API](https://sdwan-docs.cisco.com/Product_Documentation/Command_Reference/Command_Reference/vManage_REST_APIs)

#### DISCLAIMER:
<b>Please note:</b> This script is meant for demo purposes only. All tools/ scripts in this repo are released for use "AS IS" without any warranties of any kind, including, but not limited to their installation, use, or performance. Any use of these scripts and tools is at your own risk. There is no guarantee that they have been through thorough testing in a comparable environment and we are not responsible for any damage or data loss incurred with their use.
You are responsible for reviewing and testing any scripts you run thoroughly before use in any non-testing environment.
    
