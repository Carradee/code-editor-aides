code-editor-aides
======================
Code editors are useful, and they can be made even better with text filters and scripts. Here are some of mine.

## Requirements
* A code editor that allows text filters (ex. BBEdit).
* The scripting language needed by the script.
* **To run these as-is, you'll need the Mac OS**


## To Install or Uninstall
You'll need to know where your code editor stores text filters.

In the Mac OS, this will probably be under Library > Application Support. (To reach the Library folder, when in the Finder, select Go and hold down the Option key. The Library folder will appear as an option to select right under "Home" and above "Computer", not quite halfway down the list.) Once in the Application Support folder, look for the folder that has the name of your code editor, such as BBEdit or TextWrangler, which has a folder called "Text Filters" where it allows such scripts.

To install, put the uncompressed file in that folder. To uninstall, remove it the file from that folder. (You can add sub-folders to that folder for storage; the filter will still be accessible in BBEdit or TextWrangler.)

I have no idea where these would be stored in Windows or Linux.


## HTML Entities and Special Characters - folder
### PHP edition
1. Convert Special Characters to HTML Entitities.php
2. Convert HTML Entitities to Special Characters.php
* **Requires:** PHP 4 or later

### Python edition
1. Convert Special Characters to HTML Entitities.py
2. Convert HTML Entitities to Special Characters.py
* **Tested in:** Python 2.7.10 & Python 3

* **Includes:** 2 scripts
* **Purpose:** convert HTML entity codes to special characters, or special characters to HTML entity codes
* **Function:** Takes selected text or active document and converts accordingly.
* **Usage Suggestion:** Connect it to a keyboard command on your code editor.
* **Notes:** This includes all HTML entities I could find in the [dev charref](http://dev.w3.org/html5/html-author/charref) on W3.org, as of 2016. I considered combining both scripts into one, where the filter could ask the user which they wanted, but splitting it is more efficient in my workflow. Setting up a keyboard-capable 2-in-1 version might be a future project, but that would necessarily add an extra keyboard command per run, to specify which direction you want to go in.
