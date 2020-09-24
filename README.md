# Minimal-userchromeCSS
My attempt at creating a one liner interface for Firefox using the userChrome.css file. Very much a WIP.

There are also CSS tweaks for some websites.

# Installation
1. Download the files
2. Go to "about:support" in Firefox
3. Look for a line saying "Profile Folder" and open that folder (folder name will be letters/numbers followed by .default)
4. Copy the chrome folder into that folder
5. Go back to Firefox and go to "about:config"
6. type "userprof" into the page's search bar
7. If "toolkit.legacyUserProfileCustomizations.stylesheets" shows up, change it from "false" to "true"
8. Restart Firefox

# Configuring
Inside "settings.css", there are several global variables you can change. They are all explained inline.


