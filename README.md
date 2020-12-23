# macOS-utilities-Dark-Mode-Toggle



In fall 2018, Apple released macOS 10.14  Mojave, with "Dark Mode," a display preference that saves your eyes by tinting all the primary interface components a very dark grey, versus the standard "light grey and white." 

##### Activating Dark Mode involved:  

- opening a preference pane, navigating to a tab, then clicking to select 1 of 3 Appearance settings: Light (Standard) Mode, Dark Mode, or "Auto" (Change based on the time of day).  
- Auto lacks the fine control for varied situations, and manuallly changing modes is to fidgety.  

**Solved**: Someone discovered that Apple had alse released a new Automator action to control display modes, and now we can change modes in various ways.  

#### TL;DR It's Automator apps with icons that don't annoy me.  The only value of this repo is  

1. a Dark Mode icon that doen't annoy me every time I see it (I stole the design from the iOS icon), and 
2. a version of the icon that doesn't look too terrible on the Finder window Toolbar.  



### Toggle Dark Mode on Mac  

- from Spotlight (an app and icon for that) or  
- from the Finder window Toolbar (an app and icon for that).  



#### Two types of installation

1. Unzip the premade Automator app(s) and stash them anywhere 
   - **Note**: you can open them in Automator to confirm that they include only the one command, and are safe.
2. Unzip the included [Automator workflow](DarkModeTog-AutomatorWorkflow.workflow.zip) and make your own App, Service, or Workflow.  



<img alt="Dark Mode Toggle Example GIF" src="Dark-Mode-Toggle/DarkModeTog-Spotlight-Use.gif?raw=true" width="200" align="right">

### Use via Spotlight

- Just put the Automator app on your Mac, and activate it with Spotlight.  (I type  `dm` )
- I happen to use [LaunchBar](https://www.obdev.at/products/launchbar)) but Spotlight, Alfred, Keyboard Maestro, etc. will obviously be fine.  



### Use via Finder window Toolbar icon

<img alt="Dark Mode Toggle for Toolbar Example GIF" src="Dark-Mode-Toggle-for-Toolbar/DarkModeTog-Toolbar-Use.gif?raw=true" width="200" align="right">

- Put the Automator app somewhere on your Mac. (Make sure you choose the one with the Toolbar icon)
- Customize your Finder window Toolbar (right click on Toolbar, select "...Customize Toolbar")  
- Drag the Automator app to your Toolbar. Click done.  
- Test it by clicking the button. Dark Mode should toggle.  

### Icons

- I recreated the iOS Dark Mode icon [here](Dark-Mode-Toggle/DarkModeIcon_ManufacturedRecreated.icns) (Mac icon files (dot icns).  
- Then I made it into a Toolbar button [here](Dark-Mode-Toggle-for-Toolbar/DarkModeIcon_ManufacturedToolbar.icns) (same kind of file).  
