### Arctic Floorp is a Theme for the [Floorp](https://floorp.app/en) browser, inspired by the Arc browser.


## Screenshots

> Extension used for the homepage is [PixelPage 2.0](https://github.com/Trzynastek/PixelPage2.0).

<div align="center">
	<img src="assets/Normal.PNG" width="400">
	<img src="assets/Toolbar-hovered.PNG" width="400">
	<img src="assets/Tabbar-hovered.PNG" width="400">
	<img src="assets/Splitscreen.PNG" width="400">
	<img src="assets/Search.PNG" width="400">
</div>


## Installing

> **To make the process easier DO NOT restart the browser until the end.**

> **[OPTIONAL]** means that the change is not necessary for the theme to work but is to achieve results shown in the screenshots above.
> Also, the theme was developed with those settings changed as below so some elements may not be compatible.

1. Install Floorp browser (Obviously).
2. Install theme files.
	- Go to `about:profiles` page.
	- Press the "Open Folder" button found in the Root Directory under the default-release profile.
	- Move the chrome folder found in Arctic Floorp files to the profile directory.
3. Design settings.
	- Go to browser settings > Design.
	- Set "Tab Bar Style" to "Vertical Tab Bar", and enable: 

			"Collapse Vertical Tab Bar", 
			"Show the Open a new tab button inside Vertical Tab Bar".

	- Go to browser settings > Design > Lepton Settings.
 	- Choose "Use Photon design".
	- **[OPTIONAL]** Under "Automatically hide browser elements" enable: 
	
			"Automatically hide back button", 
			"Automatically hide forward button", 
			"Automatically hide buttons on the Address Bar".
		
	- **[OPTIONAL]** Under "Manage browser elements" enable: 

			"Hide Sidebar Headers", 
			"Hide Address Bar icons", 
			"Hide Bookmarks Bar icons", 
			"Hide Bookmarks Bar labels", 
			"Hide disabled context menu items".
		
	- **[OPTIONAL]** Under "Manage browser elements" disable: 

			"Enable Lepton's context menu icons"
		
	- **[OPTIONAL]** Under "Position adjustments" enable: 

			"Center text in the Address Bar".

 4. **[OPTIONAL]** Hide sidebar.
	- Go to browser settings > Browser Manager Sidebar 
	- Disable "Show the Browser Manager Sidebar".
5. **[OPTIONAL]** Toolbar cleanup.
	- Right-click on the toolbar (Where the URL input is located) and press "Customize Toolbar..."
	- Remove the following items: 

	    	"List all tabs",
    		"Floorp View",
    		"Reopen closed tab",
    		"Show Sidebars on the other side," 
    		"Firefox account", "Profile Manager".

	- Press "Done".
6. **[OPTIONAL]** Hide bookmarks toolbar.
	- Press "CTRL + SHIFT + B".
7. **[OPTIONAL]** Remove search shortcuts.
	- Go to browser settings > Search.
	- Uncheck every option under "Search Shortcuts".
8. Firefox Color Extension
	- Install the [Firefox Color](https://addons.mozilla.org/en-US/firefox/addon/firefox-color/) extension.
	- **[OPTIONAL]** In the Firefox Color configurator set the following HEX colors: 

	  		Toolbar Color: 151515, 
	  		Background Color: 151515, 
	  		Search Bar Color: 303030, 
	  		Tab Highlight Color: D9D9D9, 
	  		Popup Text: D9D9D9, 
	  		Toolbar Icons and Text: D9D9D9, 
	  		Background Tab Text Color: AFAFAF, 
	  		Search Text: D9D9D9, 
	  		Popup Background: 151515.
9. **[OPTIONAL]** `about:config` tweaks.
	- Go to `about:config`.
	- Set the following values:

			"media.videocontrols.picture-in-picture.video-toggle.position": "top"
			"sidebar.position_start": "false"
		> This setting can reduce performance but fixes an issue where video playing in a split tab can stop playing. \
 		> "media.suspend-bkgnd-video.enabled": "false"

10. Apply changes
	- Save the theme.
	- Restart the browser.

I also recommend setting shortcuts for the Split View like this:

    Open current tab on right in split view: F1
    Close split view: Alt + F1

Settings for this can be found under browser settings > Keyboard Shortcuts > Split View Actions.
