# WhatsApp Google Drive Extractor
Allows WhatsApp users on Android to extract their backed up WhatsApp data from Google Drive.  

###### BRANCH UPDATES:
v1.0 - Initial release.  
v1.1 - Added Python 3 support.  
v2.0 - Fixed gDriveFileMap after Whatsapp q requirements update
       Fixed downloadurl (the script is working again!)    
v2.5 - Added multithreading support


###### PREREQUISITES:
 1. O/S: Windows Vista, Windows 7, Windows 8, Windows 10, Mac OS X or Linux  
 2. Python 3.x - If not installed: https://www.python.org/downloads/  
 3. Android device with WhatsApp installed and the Google Drive backup feature enabled  
 4. Google services device id (if you want to reduce the risk of being logged out of Google)  
     Search Google Play for "device id" for plenty of apps that can reveal this information  
 5. Google account login credentials (username and password)  
 6. Whatsapp cellphone number as shown in backup tab on google drive website.


###### INSTRUCTIONS:
 1. Extract "WhatsApp-GD-Extractor-master.zip".  
 2. Edit the [auth] section in "settings.cfg".  
 3. Run python WhatsAppGDExtract.py from your command console.  
 4. Read the usage examples that are displayed.  
 5. Run any of the examples.  
 

###### TROUBLESHOOTING:
 1. Check you have the required imports installed (configparser and requests).  
     I.E.: pip install configparser requests  


###### CREDITS:
 AUTHOR: TripCode  

###### CREDITS:
 CONTRIBUTORS: DrDeath1122 from XDA for the multithreading backbone part
