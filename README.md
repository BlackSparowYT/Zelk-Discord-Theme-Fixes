# Zelk Discord Theme Fixes
A repository for the bugs that are fixed in the Zelk theme for better discord!

> Please note that this repo is developed using the blue theme with small tweaks from the original zelk theme. Even though i try to check out the other color schemes to make sure it doesnt causes issue it can still break.

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
Download the repository and save the files somewhere. Copy the file path. Go to the zelk theme and replace the import for the github pages with the local filepath.  
```
@import url(replace_this_with_your_file_path);
```
  
I high suggest not doing this. The files get updated regularly and you will need to keep downloading the new versions yourself. Else they will get updated automatically!


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

> ![image](https://github.com/BlackSparowYT/Zelk-Discord-Theme-Fixes/assets/117974776/3d5a66a0-9554-4766-bc30-cb8fb236a003)
> Its known that these borders arent rounded, i am still looking for a fix.

> ![image](https://github.com/BlackSparowYT/Zelk-Discord-Theme-Fixes/assets/117974776/d3075268-3c70-4b50-9d2b-08c98572b70b)
> ~~Its known that there is a weird black bar above the chat in a forum. Still looking for a fix!~~
This is now fixed, thank you lanye74 for finding the issue!

> ![image](https://github.com/BlackSparowYT/Zelk-Discord-Theme-Fixes/assets/117974776/0a7b217e-70a9-4b46-9838-639f003248bf)
> Aware of this issue that the profile pictures get dimmed out

> Also aware that multiple popups still have issues with backgrounds


