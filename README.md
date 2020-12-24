# macOS-utilities-Dark-Mode-Toggle

macOS 10.14  Mojave gave us "Dark Mode." Nice. However, I found activating Dark Mode too fidgety: Open System Prefs, get to the General preference pane, then click to select 1 of 3 Appearance settings: Light (Standard) Mode, Dark Mode, or "Auto" (Change based on the time of day).  I also thought Auto lacked the fine control for varied schedules.    

**Solved**: Someone discovered that Apple had also released a *new Automator action* to control display modes, and now we can change modes in various ways. (from Spotlight, from the dock, from the desktop, from the Toolbar, by service, by key command, etc.).  

#### What: Two Dark Mode toggle apps + icons that look okay.
1. Dark Mode Automator app using the iOS DM icon I recreated.   
2. A toolbar button version of the icon that works for me on the Finder window Toolbar.  
   <img alt="Dark Mode Toggle icon image" src="3-All-the-Icons/2-variations-and-PNG-of-icons-I-use/iOS_DM_icon_main_RECREATED_transparentOUT.png" width="100" align="left"><img alt="Dark Mode Toggle icon button image" src="3-All-the-Icons/2-variations-and-PNG-of-icons-I-use/iOS_DM_icon_Toolbar_buttonOUT.png?" width="100" align="left">
   <br/><br/>  
   <br/><br/>  

#### How: You can toggle Dark Mode by running the included app...   

- from Spotlight (an app and icon for that) or  
- from the Finder window Toolbar (an app and icon for that).  


#### Install: Unzip Automator apps

The apps already have the icons attached.  Optionally, you can make your own App, Service, or Workflow and use one of the icons. 

<img alt="Dark Mode Toggle Example GIF" src="1-Dark-Mode-Toggle/DarkModeTog-Spotlight-Use.gif?raw=true" width="200" align="right">

### Use via Spotlight

Invoke Spotlight, and type  `dm` .  Or use other launchers: [LaunchBar](https://www.obdev.at/products/launchbar) (I use), or Spotlight, Alfred, Keyboard Maestro, etc.



### Use via Finder window Toolbar icon

<img alt="Dark Mode Toggle for Toolbar Example GIF" src="2-Dark-Mode-Toggle-for-Toolbar/DarkModeTog-Toolbar-Use.gif?raw=true" width="200" align="right">

1. Select the app named "Dark Mode tb" (it has bevelled button edges).
2. Customize your Finder window Toolbar (right click on Toolbar, select "...Customize Toolbar")  
3. Drag the Automator app to your Toolbar. Click done.  
4. Test it by clicking the button. Dark Mode should toggle.  

### Icons

Some other icons and source PNGs are [here](3-All-the-Icons).  