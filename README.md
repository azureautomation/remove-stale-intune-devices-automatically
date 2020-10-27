Remove Stale Intune Devices Automatically
=========================================

            

This script will automatically remove stale intune devices for you based on a configurable number of days the device was not active.


Note that the script uses a beta / unsupported Intune Graph API endpoint and method to retrieve a token.


You need to create a Credential Object in your automation account with Global Admin rights and specify the name of the credential object as a script parameter.


If testMode is set to 1 the script will not remove any devices and just log them.


 

 

        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
