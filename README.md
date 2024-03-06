# Custom Headers is a fork of ModHeader

## The original project can be located [here](https://modheader.com/modheader)

### TODO
* migrate to manifest v3
    * https://developer.chrome.com/docs/extensions/develop/migrate
    * https://developer.chrome.com/docs/extensions/develop/migrate/to-service-workers

### Packaging Instructions

command line example: `'/cygdrive/c/Program Files/Google/Chrome/Application/chrome.exe' --pack-extension="D:\projects\modheader\oss-modheader\src"`

* **NOTE:** the `--pack-extension` argument MUST be followed directly with the `="/path/to/dir"`
    * if there is a space, or the quotes/equals sign are ommitted, the command may fail

### Installation Instructions

**Unpacked:**

1. In Chrome, visit "chrome://extensions"
2. Ensure "Developer mode" is enabled in the top-right corner
3. Click the "Load unpacked" button on the top left
4. Navigate to the source folder containing the "manifest.json" file
5. Click "Select Folder"

