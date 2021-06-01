# Minimal-userchromeCSS
A one liner interface for Firefox based on a custom userChrome.css file. Compatible with the Proton UI refresh.

Also includes some website CSS tweaks.

# Features
* One line interface to keep the focus on the webiste 
* Extraneous icons disabled to mininize clutter
* Options to display:
    * Forward/back button
    * New tab button
    * Close tab button
    * Refresh button    
* Configurable text, icon, and bar colors

# Screenshots
![New Tab](https://user-images.githubusercontent.com/35540163/120346317-42cedb80-c2c9-11eb-8240-6ba2467cf1bf.png)
![Search Results](https://user-images.githubusercontent.com/35540163/120346329-45c9cc00-c2c9-11eb-8df6-ea2b7e87bb44.png)
![App Menu](https://user-images.githubusercontent.com/35540163/120346918-d0aac680-c2c9-11eb-8078-8a2bfb587e49.png)
![Account Menu](https://user-images.githubusercontent.com/35540163/120346924-d1dbf380-c2c9-11eb-984c-8b772b518f1f.png)


# Installation
1. Download the files; extract "chrome" folder
2. Go to "about:config"
3. Type "userprof" into the page's search bar
4. If "toolkit.legacyUserProfileCustomizations.stylesheets" shows up, set to "true"
5. Go to "about:support"
6. Look for a line saying "Profile Folder" and open that folder (folder name will be letters/numbers followed by .default)
7. Move chrome folder into that folder
9. Restart Firefox

# Settings
Inside "settings.css", there are several global variables that you can change. They are all explained inline.


