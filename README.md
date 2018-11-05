# 🌚 FF Midnight - A Dark Theme for Firefox

FF Midnight is a comprehensive dark theme system for Mozilla Firefox. It features interface styling that goes further than the default built-in dark theme of the browser.

FF Midnight styles the complete interface in a dark color scheme, including Sidebars, Preference pages, View source page, PDF Viewer, all Firefox About:Pages and it also features a dark theme for popular addons such as uBLock Origin and Multi-Account Containers.

## 🎨 Theme color options

FF Midnight has 3 different dark color schemes that you can choose from:

- **Cosmos** - A dark blue theme (default)
- **Galaxy** - A dark blue/grey theme
- **Redshift** - A dark brown theme

More themes wil be added in the future.

### Opinionated styles

Some styles and colors may not be optimal for contrast or accessibility but are based on personal preferences. For example a 'flat' urlbar style and custom Tab indicators for Container tabs (find the different options in `tab-indicator.css`).

## 🛠 Extension in development

The webextension part of this repo is currently in development. The goal is that the FF Midnight can be installed as a webextension in the future. This should make installation easier and will allow for the different options to be configured in a preference panel. Until the webextension is finished you can manually install the theme by following the instructions below. Stay tuned!

## ⚙️ Installation

As a prerequisite you should use the default Firefox dark theme. This can be selected on the `about:addons#themes` page or on the Firefox Customize page. If you don't, parts of the interface may become unreadable after installation.

1. Find your profile folder ('profile names are different for everyone').  
Go to the URL `about:support` > Profile Folder > Show in Finder (MacOS) or Open folder (Windows) 
or go to `about:profiles` > Root Directory > Show in Finder (MacOS) or Open Folder (Windows)
2. Copy the contents of this repo's `\theme\` folder to the `\chrome\` folder in your Profile folder. Create the `\chrome\` folder in your Profile folder if there is none yet.  
3. Optional: To change the default **Cosmos** color scheme to **Galaxy** or **Redshift** open `userChrome.css` and `userContent.css` and follow the instructions in there. 
4. Optional: If you have the UBlock Origin and/or Multi-Account Containers extensions installed you can add theme styling to their interfaces as well.  
 Go to `about:debugging#addons` and find and copy the UUID of these addons. Open the css files for these addons, located in `\theme\css\ff-midnight\extensions\` and paste the UUID in the correct location (Instructions found in the css file).
5. Restart the browser.


## 🌌 Preview

![FF Midnight screenshot](preview/ff-midnight-preview-cosmos-1.png)

> Preferences page, Sidebar, Custom background for About:newtab, Custom Tab indicators, uBlock Origin and Multi-Account Containers panels

![FF Midnight screenshot](preview/ff-midnight-preview-cosmos-2.png)

> View Source page, About:Addons page, Page info dialog window

## 👯‍♀️ Contributions

This theme is tested on MacOS but it should work fine on Windows and Linux. If you find any bugs or have suggestions all feedback is welcome.
