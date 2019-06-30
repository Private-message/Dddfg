# Script = o365-addin-deploy.ps1
### Overview
This script will deploy the Report Message, Message Header Analyzer and FindTime Outlook Add in centrally to all uses OWA and Outlook on the desktop.
### Command line parameters
None
### Prerequisites
1. Office 365 Central Deployment module is loaded
### Variables
None
### Operation
The Office 365 Central Deployment module currently does not support MFA. If your tenant has MFA enabled then you will need to use the web interface to provision these add ins.<br/><br/>
The command new-organizationaddin is used to deploy addins from the Office store. Note, you may need to change the location to suite your environment.<br/><br/>
The command set-organizationaddin is then executed to enable these addins within the tenant.<br/><br/>
The command set-organizationaddin assignments is executed to roll out these addins to all users. 