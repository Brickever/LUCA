LUCA Changes
============


0.3
---
*Released Unknown*

* Small message formatting
* Added missing `</head>` tag for HTML document
* Fixed hard-coded download folder location
* Added Python hashbang
* Write window title using program name and version number
* Changed app closing method
* Converted most script usage of string literals to use the format method
* Added `setup.py`
* Converted all whitespace from tabs to 4 spaces (per Python standard)
* Updated HTML document writing to use recommended `with` handle
* Updated error message to include user input
* Added global variables containing program name and version
* Added GPL block to `LUCA.py` and `setup.py`
* Added a few script comments
* Improved layout of written HTML document
* If download folder does not exist, make it. Otherwise, start the download
* Converted non-HTML file writing to use recommended `with` handle
* Fixed exit code number when closing the program
* Cleaned up saving path for both HTML and non-HTML files
* Added "Successful Download" message
* Added number of files downloaded into "Successful Download" message
* Added exit routine after finishing the download
* Added message to inform user their files are downloading
* Display list of downloaded file (LUCA's non-GUI version of a progress bar)
* Updated "progress bar" to display filename as soon as it is downloaded, not after everything was downloaded
* Added error handling for when LUCA does not find any links when searching on the Creation Lab for an entered username
* Updated: username entered are now case-insensitive.

0.2
---
*Released May 29, 2013*

* Added invalid website check
* Updated user input to ask for Creation Lab `username` only, rather than `memberid` and `username`
* Added code to get `memberid` from website, and check it against `username`
* Variable names update
* Added error handling for a username that does not match with the one found online.
* Removed invalid website check (no longer needed)

0.1
---
*Released Never*