- CHECK NETWORK CONNECTIVITY - Making sure a network connection is established. This can be either a wifi or wired connection. Can the device access the services described in Windows Autopilot networking requirements
- REVIEW CONFIGURATION: Has Azure Active Directory and Microsoft Intune been configured as specified in Windows Autopilot configuration requirements.
- User authentication issues. Making sure the user enters the correction authentication credentials.
- Autopilot OOBE Behavior: Are the expected OOBE screens displayed? Is the Azure AD credentials page customized with organization-specific details as expected? (If the user is not being prompted to put in credentials try a sysprep command in the run command)
- Review logs that are automatically collected upon Autopilot failure

