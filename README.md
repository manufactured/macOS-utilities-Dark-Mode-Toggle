# macOS utilities - Dark Mode Toggle shortcut



### ⚠️ This repo is now [this repo](https://github.com/manufactured/macOS-utilities-Dark-Mode-Toggle-shortcut).  Sorry for the confusion.  

---





### macOS first featured "Dark Mode" in Mojave (10.14).  

**Problem**: Too many steps to activate. Open System Prefs, get to the General preference pane, then click to select 1 of 3 Appearance settings: Light (Standard) Mode, Dark Mode, or "Auto" (Change based on the time of day).  I also thought Auto lacked the fine control for varied schedules.    

**Solved**: Apple had thought of this, and released a *new Automator action* to control display modes, and now we can change modes in various ways. (from Spotlight, from the dock, from the desktop, from the Toolbar, by service, by key command, etc.).  

### This repo: Dark Mode toggle app x2 based on iOS Dark Mode icon.  
App+Icon: iOS Dark Mode (I recreated in Pixelmator).  
<img alt="Dark Mode Toggle icon image" src="iOS_DM_icon_main_RECREATED_transparentOUT.png" width="60" align="left">  
<br/><br/>
<br/>Icon: iOS: Dark Mode for Finder window Toolbar (in default "button" style)    
<img alt="Dark Mode Toggle icon button image" src="iOS_DM_icon_Toolbar_buttonOUT.png?" width="59" align="left">  
<br/><br/>

### How: You can toggle Dark Mode by running the included apps...   

- From Spotlight and elsewhere: 


- By clicking the Dark Mode icon in the Finder window Toolbar.  

  

**To Install**: Unzip Automator apps. The apps already have the icons attached.   

You can also make your own App, Service, or Workflow and use one of the icons on your app.    

<br/><br/>

<img alt="Dark Mode Toggle for Toolbar Example GIF" src="DarkModeTog-Spotlight-Use-Finder+Chrome-by_Manufactured.gif?raw=true" width="200" align="right">  

### Option 1. Use via Spotlight

Invoke Spotlight, and type  `dm` .   

Or use other launchers: I use [LaunchBar](https://www.obdev.at/products/launchbar), or you can use [Spotlight](https://support.apple.com/en-gb/HT204014), [Alfred](https://www.alfredapp.com/), [Quicksilver](https://qsapp.com/), [Keyboard Maestro](https://www.keyboardmaestro.com/main/), etc.  

*Additional functionality:* Set apps to follow System Dark Mode status.  

Many Mac apps can change Dark Mode status based on System Dark Mode status.  The "[Dark Reader](https://darkreader.org/)" extension for Mac browsers Safari (paid extension) and Google Chrome (free extension) supports Dark Mode for web pages as well.  (This GIF shows Finder and Chrome Dark Mode following System settings.)  

<br/><br/>

### Option 2. Use via Finder window Toolbar icon

<img alt="Dark Mode Toggle for Toolbar Example GIF" src="DarkModeTog-Toolbar-Use-by_Manufactured.gif?raw=true" width="200" align="right">  

#### 2a. Install the unzipped app "Dark Mode tb" into your Finder window Toolbar. 

1. Select the app named "Dark Mode tb" (it has bevelled button edges).
2. Customize your Finder window Toolbar (right click on Toolbar, select "...Customize Toolbar")  
3. Drag the Automator app to your Toolbar. Click done.  

#### 2b. Test it by clicking the button. Dark Mode should toggle.   

---


### Icons

Some other icons and source PNGs are [here](3-All-the-Icons).   
