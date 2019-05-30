# Ruby-SFTP-Project
This Ruby script is moving files from one directory to a render box using SFTP/SSH gems.  It is also copying the original files into an archive folder, and moving erroneous files into a rework folder.  Variables uid, facility, numerator, and var are what this script is looking for as part of the filenames in an outgoing folder. Files which are moved over to SFTP render box have also been cleaned of "blank" unicodes, and commas are replaced by pipe delimiters as part of HL7 format.

Considerations:
1. Potentially construct functions to take into consideration of global variables.
2. Use config files to store separate user/passwords for all the SFTP portals.
