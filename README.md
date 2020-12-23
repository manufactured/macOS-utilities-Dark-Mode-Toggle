# macOS-utilities-Dark-Mode-Toggle

macOS 10.14  Mojave gave us "Dark Mode." Nice. However, I found activating Dark Mode too fidgety: Open System Prefs, get to the General preference pane, then click to select 1 of 3 Appearance settings: Light (Standard) Mode, Dark Mode, or "Auto" (Change based on the time of day).  I also thought Auto lacked the fine control for varied schedules.    

**Solved**: Someone discovered that Apple had also released a *new Automator action* to control display modes, and now we can change modes in various ways. (from Spotlight, from the dock, from the desktop, from the Toolbar, by service, by key command, etc.).  

#### TL;DR Two Dark Mode toggle apps + icons that don't annoy me.
1. Dark Mode Automator app using the iOS DM icon I recreated.   

A version of the icon that doesn't look too terrible on the Finder window Toolbar.  
<img alt="Dark Mode Toggle icon image" src="3-All-the-Icons/2-variations-and-PNG-of-icons-I-use/iOS_DM_icon_main_RECREATED_transparentOUT.png" width="100" align="left"><img alt="Dark Mode Toggle icon button image" src="3-All-the-Icons/2-variations-and-PNG-of-icons-I-use/iOS_DM_icon_Toolbar_buttonOUT.png?" width="100" align="left">
<br/><br/>  
<br/><br/>  

#### You can toggle Dark Mode by running the included app...   

- from Spotlight (an app and icon for that) or  
- from the Finder window Toolbar (an app and icon for that).  


#### Two types of installation

1. Unzip the premade Automator app(s) and stash them anywhere 
   - **Note**: you can open them in Automator to confirm that they include only the one command, and are safe.
2. Unzip the included [Automator workflow](DarkModeTog-AutomatorWorkflow.workflow.zip) and make your own App, Service, or Workflow.  


<img alt="Dark Mode Toggle Example GIF" src="1-Dark-Mode-Toggle/DarkModeTog-Spotlight-Use.gif?raw=true" width="200" align="right">

### Use via Spotlight

- Just put the Automator app on your Mac, and activate it with Spotlight.  (I type  `dm` )
- I happen to use [LaunchBar](https://www.obdev.at/products/launchbar)) but Spotlight, Alfred, Keyboard Maestro, etc. will obviously be fine.  



### Use via Finder window Toolbar icon

<img alt="Dark Mode Toggle for Toolbar Example GIF" src="2-Dark-Mode-Toggle-for-Toolbar/DarkModeTog-Toolbar-Use.gif?raw=true" width="200" align="right">

- Put the Automator app somewhere on your Mac. (Make sure you choose the one with the Toolbar icon)
- Customize your Finder window Toolbar (right click on Toolbar, select "...Customize Toolbar")  
- Drag the Automator app to your Toolbar. Click done.  
- Test it by clicking the button. Dark Mode should toggle.  

### Icons

All the icons and a couple PNGs are [here](3-All-the-Icons).  