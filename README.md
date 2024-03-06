Custom Headers is a fork of ModHeader

The original project can be located here: https://modheader.com/modheader

TODO:
    investigate/disable cloud syncronization
        src/background.js:265:function saveStorageToCloud() {
        src/background.js:364:      saveStorageToCloud();
        src/background.js:371:      saveStorageToCloud();

Packaging Instructions
command line example:
'/cygdrive/c/Program Files/Google/Chrome/Application/chrome.exe' --pack-extension="D:\projects\modheader\oss-modheader\src"

NOTE:
the "--pack-extension" argument MUST be followed directly with the '="/path/to/dir"'
if there is a space, or the quotes/equals sign are ommitted, the command may fail

Installation Instructions

Unpacked:
In Chrome, visit "chrome://extensions"
Ensure "Developer mode" is enabled in the top-right corner
Click the "Load unpacked" button on the top left
Navigate to the source folder containing the "manifest.json" file
Click "Select Folder"

