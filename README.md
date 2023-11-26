# Auto File Organizer
This Python script automatically organizes files in a specified directory based on their file types. It uses the watchdog library to monitor the directory for any changes.

## Features
+ Automatically moves new files from a source directory to appropriate destination directories based on file type.
+ Supports a variety of file types including images, videos, audio files, documents, zip files, and Python files.
+ If a file with the same name already exists in the destination directory, it renames the file by appending a number to the filename to make it unique.
+ Logs every file move operation.
## How to Use
1: Set your source directory and destination directories at the top of the script.  
2: Run the script. It will keep running and monitor the source directory for any new files.  
3: Any new file added to the source directory will be automatically moved to the appropriate destination directory based on its file type.    
## Dependencies
This script requires the following Python libraries:  

+ os  
+ scandir
+ rename
+ exists
+ join
+ move
+ sleep
+ logging
+ watchdog
You can install them using pip:
`pip install watchdog`    
OR 
`py -m pip install watchdog`
## Note
This script is intended to be run continuously in the background. To stop the script, use a keyboard interrupt (Ctrl+C).

# Disclaimer
Please use this script responsibly. The author is not responsible for any data loss that may occur as a result of using this script. Always test the script on non-important data first.