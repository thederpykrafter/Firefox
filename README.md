# tdk.firefox

<a href="https://wakatime.com/badge/github/thederpykrafter/tdk.firefox"><img src="https://wakatime.com/badge/github/thederpykrafter/tdk.firefox.svg" alt="wakatime"></a>

My slightly modified Firefox CSS theme<br>
Use [Firefox Color Addon](https://color.firefox.com/?theme=XQAAAAJCAQAAAAAAAABBqYhm849SCia3ftKEGccwS-xMDPrv2Sw6Caq-qy5QgqeHG4K15QcrDwIkmgjiMt982DgWhmsaa6HAbqbuA9Kv-Hq9_l_9uOBAFFpKWQIi-cXmmFHpXqEANeTRGpb8ehdkfTYPP9U_ZXCMLd5yNKzlg8IIqeGOhCLC837nhim2wImITx_i2UTz-_eciFAPvPH5UV743DMLLovf6HvfksE29265GnPDUyC6qaFJsnpdmqP756niHtZBUii_qYUB6Cd8c9W4lY6dGRJ__-dRzAA)<br>

[Original Theme](https://github.com/hakan-demirli/Firefox_Custom_CSS) by 
[hakan-demirli](https://github.com/hakan-demirli)<br>

Firefox CSS theme to maximize the vertical space of your monitor.<br>
Copy this theme to your firefox profile folder.<br>
To find firefox profile navigate to `about:support` and under Profile Folder click open folder

#### Windowed (rounded corners from windows)
![windowed preview](pics/windowed.png?raw=true)
#### Maximized
![maximized preview](pics/maximized.png?raw=true)
#### Fullscreen (autohide top toolbar)
![fullscreen preview](pics/fullscreen.png?raw=true)

## Contents
- [Contents](#contents)
- [Compatibilty](#compatibilty)
- [Features](#features)
- [Suggested Tweaks](#suggested-tweaks)
- [Toggle PDF reader dark mode](#toggle-pdf-reader-dark-mode)
- [Install](#install)
- [Credits](#credits)

## Compatibilty
Supported:
* Gnome, KDE, Hyprland, i3wm
* Windows 10, Windows 11

Not supported:
* Windows 8.1
Problem: [Missing Toolbar Icons](https://github.com/hakan-demirli/Firefox_Custom_CSS/issues/7)
*  MacOS Catalina 10.15.5 and Big Sur 11.6
Problem: [No toolbar!](https://github.com/hakan-demirli/Firefox_Custom_CSS/issues/3)

## Features
 * Horizontal tabs are removed. Use [Sidebery](https://addons.mozilla.org/en-US/firefox/addon/sidebery/) or [Tree Style Tab](https://addons.mozilla.org/en-US/firefox/addon/tree-style-tab/)
 * Dark mode for the default PDF reader:<br>
   ![alt text](pics/dark_mode.png?raw=true)

 * Dark mode for hover URL menu:<br>
 ![alt text](pics/dark_hover_menu.png)

 * Thinner scroll bars:<br>
 ![alt text](pics/scroll_bar.png)

## Suggested Tweaks
**Enable Compact Mode**<br>
_about:config > browser.compactmode.show > True_

**Startup Image**<br>
_about:config > browser.startup.preXulSkeletonUI > False_

**Save Startup Tabs**<br>
_Settings > General > Startup > Open previous windows and tabs > True_
(Otherwise size of the top sites will change everytime you open the browser.)

**Prevent Pinned Tabs From Loading**
_browser.sessionstore.restore_pinned_tabs_on_demand > True_

## Toggle PDF reader dark mode
The PDF viewer dark mode is active by default. To deactivate it, just add ```?n``` to the end of your pdf URL.<br>
![alt text](pics/pdf_dark_mode.png)

## Install
* Follow the steps below to open the necessary directory:
  * Application Menu > Help > More troubleshooting information > Profile Folder > Open Folder
* Create a new folder and name it `chrome`
* Copy all of the files into the `chrome` folder
* Enable user scripts and compact mode:
  * Go to the `about:config` URL
  * Set `toolkit.legacyUserProfileCustomizations.stylesheets` to true
  * Set `browser.compactmode.show` to true
  * Right click Toolbar > Customize Toolbar > Density (Bottom Left) > Compact
* Install vertical tab extension: [Sidebery](https://addons.mozilla.org/en-US/firefox/addon/sidebery/) or [Tree Style Tab](https://addons.mozilla.org/en-US/firefox/addon/tree-style-tab/)
* Reopen Firefox
* Customize the Sidebery/TreeStyleTabs and Toolbar to your hearts content.
## Credits
  * [r/FirefoxCSS](https://www.reddit.com/r/FirefoxCSS/)
