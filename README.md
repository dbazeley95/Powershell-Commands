# Powershell-Commands:


# Set Office 365 user account password to prompt change on next login;
Set-MsolUserPassword -UserPrincipalName user@domain.com -ForceChangePasswordOnly $true -ForceChangePassword $true
