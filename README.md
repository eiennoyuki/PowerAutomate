# PowerAutomate
PowerAutomate Flows I've Created for SP sites I created and help manage cross-divisionally.  
There are beautified version of each JSON file.  
Confidential information has been modified.  

## LAX_ARCHIVE_LOST_FOUND
* This is an O365 Power Automate Flow that runs daily on a SP List.  It cross references a date column and migrates any data older than 30 days into duplicate, archived list that is hidden from users based on configured SP permission groups.

## SP_LIST_AUTOMATIC_NOTIFICATIONS
* This is an O365 Power Automate Flow that runs daily on a Teams/SP List.  It is a parallel flow that cross references various date columns and automatically initiates emails to the team to provide CSS table-formatted information of daily actionables with attachments as necessary.
