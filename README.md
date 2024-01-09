## 🎂 How to bring back Old Steam UI? 🎂

* Close completely Steam 
* Create Shortcut for Steam.exe
* Right Click on Shortcut
* Properties
* Target (It should have path to original .exe file)
Default `"C:\Program Files\Steam"` or Your Location
* Paste This in after Path from previous step (It will download old version of Steam)
```
-forcesteamupdate -forcepackagedownload -overridepackageurl http://web.archive.org/web/20230531113527if_/media.steampowered.com/client -exitsteam
```
* Open Steam via Shortcut
* Wait until it finish update and will close
* Delete previously pasted code (remember to not delete path to .exe file)
* Open Steam Main Folder
* In this folder create File "steam.cfg" (.cfg Needs To Be File Extension, not steam.cfg.txt)
* Paste This in our "steam.cfg" File (It will prevent form Automatic Updates)
```cfg
BootStrapperInhibitAll=Enable
BootStrapperForceSelfUpdate=False
```
* Open Steam, should looks normal again

## 📃 Friend List (Fix) 📃

All documentation and how-to information, including installation instructions, is located on [this (open me)](https://github.com/TiberiumFusion/FixedSteamFriendsUI/wiki/How-to-Install) page.
