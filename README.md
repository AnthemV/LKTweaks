
# The LK Webapp
![](https://github.com/AnthemV/LKTweaks/blob/main/Screenshots/LkWebapp.png?raw=true)

**The very simple eighteen step process to achive this is as follows:**
1. Install Firefox.
2. Install the [Progressive Web Apps for Firefox](https://addons.mozilla.org/en-US/firefox/addon/pwas-for-firefox/) extension.
3. Install LegendKeeper as a PWA.
4. Download and extract the `chrome` folder from the releases section.
5. Press `f6` and go to `about:support`
6. Scroll down slightly, and locate where it says "Profile Directory." Click on the button that says `Open Directory`
7. Move the downloaded `chrome` folder to this directory. 
8. Press `f6` and go to `about:config`
9.  Set the value `toolkit.legacyUserProfileCustomizations.stylesheets` to `true`
10. Set the value `firefoxpwa.enableHidingIconBar` to `true`
11. You can now press `Ctrl`+`Alt` to toggle the icon/tab bar.
12. Press `f6` and go to `about:preferences`
13. Scroll down and enable `Show browser tabs and enable using multi-tabbed web apps`
14. Press `f6` and go to `https://addons.mozilla.org/en-US/firefox/addon/styl-us/`
15. Install the extension Stylus.
16. Press `f6` and go to `https://github.com/AnthemV/LKTweaks` (hey, that's here!)
17. Install the Webapp Style from below.
18. Install any other styles you desire, then restart your LegendKeeper PWA!



  ## WebApp Style
  
<p align="left">
  <a target="_blank" rel="noopener noreferrer" href="https://github.com/AnthemV/LKTweaks/raw/main/LKTweaks-Webapp.user.styl">
    <img src="https://img.shields.io/badge/Install%20directly%20with-Stylus-116b59.svg?longCache=true&style=flat"/>
  </a>
 </p>
 
 **Disclaimer:**
This style was made with the scaling and zoom of my personal LK instance in mind. If anything on your end differs, the placement of the window buttons is likely to be messed up. You can fix this by editing a file within the `chrome` folder we extracted and placed earlier. Go to `location-of-your-profile-directory/chrome/firefox-gnome-theme/customChrome.css` The values to edit are clearly marked out at the top. 

![](https://github.com/AnthemV/LKTweaks/blob/main/Screenshots/Howtoedit.png?raw=true)

# Individual Styles 

### Usage
Install the browser extension *Stylus* ([Firefox.](https://addons.mozilla.org/en-US/firefox/addon/styl-us/) [Chrome.](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne)), then click the "Install directly with Stylus" buttons.

These styles are made for the legacy site, and (mostly) won't work on public worlds.


## World Image Style
  
<p align="left">
  <a target="_blank" rel="noopener noreferrer" href="https://github.com/AnthemV/LKTweaks/raw/main/LKTweaks-World-Image.user.styl">
    <img src="https://img.shields.io/badge/Install%20directly%20with-Stylus-116b59.svg?longCache=true&style=flat"/>
  </a>
 </p>
  
Adds a cover image to the project browser. You have to manually specify the world you want this to apply on. Open the style and scroll to the bottom. Only works on worlds with shortcuts at the top. You can change the image that's displayed by changing the url in the top two code blocks of the style. The top one applies while using the dark theme, and the bottom one while using the light theme.


![](https://github.com/AnthemV/LKTweaks/blob/main/Screenshots/exampleworld.png?raw=true)


 
   Before             |  After 
:-------------------------:|:-------------------------:
![](https://github.com/AnthemV/LKTweaks/blob/main/Screenshots/BeforeWorldImage.png?raw=true)  |  ![](https://github.com/AnthemV/LKTweaks/blob/main/Screenshots/AftterWorldImage.png?raw=true)



## Table Style
  
<p align="left">
  <a target="_blank" rel="noopener noreferrer" href="https://github.com/AnthemV/LKTweaks/raw/main/LKTweaks-Tables.user.styl">
    <img src="https://img.shields.io/badge/Install%20directly%20with-Stylus-116b59.svg?longCache=true&style=flat"/>
  </a>
 </p>
  
Makes tables look nicer. The examples here are using some messy alignment things I'm still playing with. It would cause more issues if I included them.

 
   Before             |  After 
:-------------------------:|:-------------------------:
![](https://github.com/AnthemV/LKTweaks/blob/main/Screenshots/BeforeTables.png?raw=true)  |  ![](https://github.com/AnthemV/LKTweaks/blob/main/Screenshots/AfterTables.png?raw=true)


  ## Header Style
  
<p align="left">
  <a target="_blank" rel="noopener noreferrer" href="https://github.com/AnthemV/LKTweaks/raw/main/LKTweaks-Headers.user.styl">
    <img src="https://img.shields.io/badge/Install%20directly%20with-Stylus-116b59.svg?longCache=true&style=flat"/>
  </a>
 </p>
  
Decreases the spacing between headers and paragraphs.

 
   Before             |  After 
:-------------------------:|:-------------------------:
![](https://github.com/AnthemV/LKTweaks/blob/main/Screenshots/BeforeHeaaders.png?raw=true)  |  ![](https://github.com/AnthemV/LKTweaks/blob/main/Screenshots/AfterHeaders.png?raw=true)


## Embed Tweaks 

<p align="left">
  <a target="_blank" rel="noopener noreferrer" href="https://github.com/AnthemV/LKTweaks/raw/main/LKTweaks-Embeds.user.styl">
    <img src="https://img.shields.io/badge/Install%20directly%20with-Stylus-116b59.svg?longCache=true&style=flat"/>
  </a>
 </p>

This style alters the Youtube and Spotify embeds, giving them some extra padding to stay consistant with other sidebar blocks. It also alters the Youtube embed to work much better at a small size. 

Fair warning, this will likely mess up YouTube embeds on other sites. I recomend installing LegendKeeper as a *Progressive Web App* in order to get around this. Alternatively, you can simply keep the style turned off whenever you're not using LegendKeeper. It can be toggled from the extension.

#### Progressive Web App Options
* [Firefox](https://addons.mozilla.org/en-US/firefox/addon/pwas-for-firefox/) - Easy, uses a seperate extension list from the main browser.
* [Chrome](https://support.google.com/chrome/answer/9658361) - More difficult, requires another browser or profile for seperate extensions.


Before             |  After 
:-------------------------:|:-------------------------:
![](https://github.com/AnthemV/LKTweaks/blob/main/Screenshots/Screenshot%20from%202023-03-03%2002-07-55.png?raw=true)  |  ![](https://github.com/AnthemV/LKTweaks/blob/main/Screenshots/Screenshot%20from%202023-03-03%2002-07-31.png?raw=true)
![](https://github.com/AnthemV/LKTweaks/blob/main/Screenshots/Screenshot%20from%202023-03-03%2002-08-05.png?raw=true)  |  ![](https://github.com/AnthemV/LKTweaks/blob/main/Screenshots/Screenshot%20from%202023-03-03%2002-07-20.png?raw=true)

 
 ## Rounding Style 
 
<p align="left">
  <a target="_blank" rel="noopener noreferrer" href="https://github.com/AnthemV/LKTweaks/raw/main/LKTweaks-Rounding.user.styl">
    <img src="https://img.shields.io/badge/Install%20directly%20with-Stylus-116b59.svg?longCache=true&style=flat"/>
  </a>
 </p>
 
This adds rounded corners to quote blocks, and makes the rounded corners of images more pronounced.

 
  Before             |  After 
:-------------------------:|:-------------------------:
![](https://github.com/AnthemV/LKTweaks/blob/main/Screenshots/BeforeRounding2.png?raw=true)  |  ![](https://github.com/AnthemV/LKTweaks/blob/main/Screenshots/AfterRounding2.png?raw=true)


  ## Search Style
  
<p align="left">
  <a target="_blank" rel="noopener noreferrer" href="https://github.com/AnthemV/LKTweaks/raw/main/LKTweaks-Search.user.styl">
    <img src="https://img.shields.io/badge/Install%20directly%20with-Stylus-116b59.svg?longCache=true&style=flat"/>
  </a>
 </p>
  
Moves the search icon into the same section as the other bottom blocks. 

 
   Before             |  After 
:-------------------------:|:-------------------------:
![](https://github.com/AnthemV/LKTweaks/blob/main/Screenshots/BeforeSearch2.png?raw=true)  |  ![](https://github.com/AnthemV/LKTweaks/blob/main/Screenshots/AfterSearch2.png?raw=true)



## Menu Style 

<p align="left">
  <a target="_blank" rel="noopener noreferrer" href="https://github.com/AnthemV/LKTweaks/raw/main/LKTweaks-Menus.user.styl">
    <img src="https://img.shields.io/badge/Install%20directly%20with-Stylus-116b59.svg?longCache=true&style=flat"/>
  </a>
 </p>

This changes the appearance of menu items in LK. 

 
 Before             |  After 
:-------------------------:|:-------------------------:
![](https://github.com/AnthemV/LKTweaks/blob/main/Screenshots/BeforeMenus.png?raw=true)  |  ![](https://github.com/AnthemV/LKTweaks/blob/main/Screenshots/AfterMenus.png?raw=true)
 
 
 
  ## Preview Window Border Style
  
<p align="left">
  <a target="_blank" rel="noopener noreferrer" href="https://github.com/AnthemV/LKTweaks/raw/main/LKTweaks-PreviewBorder.user.styl">
    <img src="https://img.shields.io/badge/Install%20directly%20with-Stylus-116b59.svg?longCache=true&style=flat"/>
  </a>
 </p>
  
This adds a small border to the link preview windows, making them easier to differentiate from the background.

 
   Before             |  After 
:-------------------------:|:-------------------------:
![](https://github.com/AnthemV/LKTweaks/blob/main/Screenshots/BeforeBorder2.png?raw=true)  |  ![](https://github.com/AnthemV/LKTweaks/blob/main/Screenshots/AfterBorder2.png?raw=true)


# Experimental Styles 
Thses styles aren't recommended for typical use. Install them if you want to alter them for mockups or test potential functionality.

  ## Sidebar Image
  
<p align="left">
  <a target="_blank" rel="noopener noreferrer" href="https://github.com/AnthemV/LKTweaks/raw/main/Experiment-Sidebar-Image.user.styl">
    <img src="https://img.shields.io/badge/Install%20directly%20with-Stylus-116b59.svg?longCache=true&style=flat"/>
  </a>
 </p>
 
 This adds an image to the background of the first block in the sidebar. The image you use applies to all sidebars. Dark theme only right now (because making the gradients consistant is hard).  




