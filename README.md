> [!IMPORTANT]  
> I am updating this theme to a v2 if you still would like the old version (v1) please select that branch and copy to code in `main-fixes.css` and paste it in you zelk theme at the bottom

> [!IMPORTANT]  
> I make these fixes based on my own color scheme. I have seen some issues where running light colors can break this. I suggest not using any light accent colors! (FYI i run #3265a2 as my accent color). Sometimes i try to check the other themes aswell but i cant always do it.


# Zelk Discord Theme Fixes
A repository for the bugs that are fixed in the Zelk theme for better discord!

## How does it work?
In the current zelk theme there are quite a lot of bugs that mostly likely wont be updated. So i have made this repository to fix these bugs. its really simple as it can be fixed with just a few lines of CSS.
Make sure to check out the original Zelk theme over here: https://betterdiscord.app/theme/Zelk

## How do i use it?
Make sure you have the zelk theme installed in better discord. 
Edit the theme and add this line after the other @imports in the zelk theme.
```
@import url(https://blacksparowyt.github.io/Zelk-Discord-Theme-Fixes/main-fixes.css);
```

## Can i use this locally?
If you rather not link to the github pages and want to use a local version that is possible.
download the repository. save the files somewhere and copy the file path to it. Go to the zelk theme and replace the import for the github pages to the online files with the local filepath.  
  
I high suggest not doing this. The files get updated regularly and you will need to keep downloading the new versions yourself. Else they will get updated automatically!


## Addons:

### Custom icon:
Requested in [[FR] Custom Home Logo](https://github.com/BlackSparowYT/Zelk-Discord-Theme-Fixes/issues/20) you can now change the default discord logo to any image you want.

To use this add this line in the zelk theme:
```
@import url(https://blacksparowyt.github.io/Zelk-Discord-Theme-Fixes/cust-icon.css);
```
Then scroll to the bottom of the zelk theme and add this:
```
:root {
    --cust-home-icon: url('put_link_to_image_here');
}
```
Make sure to replace the `put_link_to_image_here` with the link to your image. I suggest only using a square transparent picture!

## Compatibility with other plugins?
These fixes have compatibility with other plugins. current it supports: Radial Status & Show Badges In Chat.


### Radial Status:
To add the fixes for radial status add this line:
```
@import url(https://blacksparowyt.github.io/Zelk-Discord-Theme-Fixes/radialstatus-fixes.css);
```
after the intial @import. Also make sure you have installed the radial status theme!

### SBIC (Show Badges In Chat):
To add the fixes for radial status add this line:
```
@import url(https://blacksparowyt.github.io/Zelk-Discord-Theme-Fixes/sbic-fixes.css);
```
after the intial @import. Also make sure you have installed the Show Badges In Chat Plugin!


## Your help!
If you find any bugs in the Zelk theme open a issue here so we can add it!!! 
Want support for another plugin? Again open a issue here!


## Known Issues
I would always appricate you guys helping me fix these issues!

> Also aware that multiple popups still have issues with backgrounds


