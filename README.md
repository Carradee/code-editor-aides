# code-editor-aides
Code editors are useful, and they can be made even better with text filters and scripts. Here are some of mine.

## Requirements
* A code editor that allows text filters (ex. BBEdit).
* The scripting language needed by 

## HTML Entities & Special Characters
1. Convert Special Characters to HTML Entitities.php
2. Convert HTML Entitities to Special Characters.php
* **Requires:** PHP 4 or later

* **Includes:** 2 scripts
* **Purpose:** convert HTML entity codes to special characters, or special characters to HTML entity codes
* **Function:** Takes selected text or active document and converts accordingly.
* **Usage Suggestion:** Connect it to a keyboard command on your code editor.
* **Notes:** This includes all HTML entities I could find in the [dev charref](http://dev.w3.org/html5/html-author/charref) on W3.org, as of 2016. I considered combining both scripts into one, where the filter could ask the user which they wanted, but splitting it is more efficient in my workflow. Setting up a keyboard-capable 2-in-1 version might be a future project, but that would necessarily add an extra keyboard command per run, to specify which direction you want to go in.
