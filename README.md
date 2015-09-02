# mintsetup
A BASH script to help users set up and maintain a new Linux Mint / Ubuntu installation

**Build Environment:** Linux Mint 17.2 KDE amd64, Sublime Text 3

**Notes:**
- This is an update of an old command-line project, and it is a work in progress.

**To do:**
- Add in an 'offline' menu as well as the default 'online' version, and remove the Main Menu text regarding Internet connection availability.
- Add better desktop detection to determine what desktop is being used. This can be accessed by viewing the $DESKTOP_SESSION variable.
- Optimise all root commands to call sudo *only* when required to increase security.

**Change Log:**
- **16/08/2015**
	- Updated the script to detect KDE, MATE and Ubuntu desktops and have removed some useless functionality.
	- Some functions have also been streamlined and optimised for the sake of efficiency.
	- A link to this repository is now inside the source code.
- **18/08/2015**
	- Updated the indentation of 'README.md' and 'mintsetup' to use standard tabs.
- **02/09/2015**
	- Included some en-GB dependencies for LibreOffice and Mozilla Thunderbird.
	- Swapped 'clamtk' in 'installFavourites' for 'clamav'.