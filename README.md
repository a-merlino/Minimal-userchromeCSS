# Minimal-userchromeCSS
A one liner interface for Firefox based on a custom userChrome.css file. Still a work in progress, although currently very usable.

Also includes CSS tweaks for some websites.

# Screenshots
![Screenshot (14)](https://user-images.githubusercontent.com/35540163/114794149-d8360080-9d59-11eb-8d90-48f6d49d8d2a.png)
![Screenshot (21)](https://user-images.githubusercontent.com/35540163/114794153-d9ffc400-9d59-11eb-8889-157e27d5ad07.png)


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
Inside "settings.css", there are several global variables that you can change. They are all explained inline.


