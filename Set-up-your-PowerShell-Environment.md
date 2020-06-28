1. Run PowerShell environment as an administrator on your local machine<br><br>
2. Run the script [o365-setup.ps1](https://github.com/directorcia/Office365/blob/master/o365-setup.ps1)<br><br>
3. Download and install the [Powershell module for Skype for Business](https://github.com/directorcia/Office365/blob/master/o365-setup.ps1)<br><br>
4. Install the Exchange Online MFA Powershell module - [Video](https://www.youtube.com/watch?v=EnmwLqdtDCM)<br><br>
5. Run the command:<br><br> <b>set-executionpolicy -executionpolicy bypass -scope currentuser -force</b> <br><br>to allow custom scripts to execute in your environment. You only need to run this command once.<br><br>
6. Run the script [o365-connect-exov2.ps1](https://github.com/directorcia/Office365/blob/master/o365-connect-exov2.ps1) to verify connection to Exchange Online<br><br>
7. Run the script [o365-mx-check.ps1](https://github.com/directorcia/Office365/blob/master/o365-mx-check.ps1) to verify that script commands work on service<br><br>

[Overview Video](https://www.youtube.com/watch?v=KsE3ENgTky8)
