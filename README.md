### Getting Started
This application was built using [Porting Kit](https://www.portingkit.com/)

**Note:** This app is a container. So login information and servers are saved within. SO PLEASE DO NOT SHARE your .app with anyone else.
***
#### Installation
1.  Navigate to the **[Latest Release](https://github.com/suxhi-space/OSFR-Launcher-MacOS/releases/latest)**.
2.  Download the latest `OSFRLauncher.dmg`.
    > **Note:** For 1.0.0 We recommend you Select Arm for M series Macs and x86 of for Intel Macs. (OSFRLauncher_***.dmg)
3.  Open and drag into application folder.

#### How to Play
1.  Launch the application..
    > **Note:** You might need to approve the app so go to System Settings > Privacy & Security. Scroll down and see if there's a message about the app being blocked and click "Open Anyway" (you might need to unlock with your password).
2.  Enter a server URL from a **Known** host.
    > **Note:** Sul's Server and files have been added in by default for easy use. IF you want a version without Sul's files preloaded please let me know in the discord.
3.  Click **"Play"**.
4.  Log in with your account details and enjoy the game!


---
#### Zip Guide:
1. Open the zip then drag the app to your applications folder.


---
#### Can't open DMG:
- Check System Settings: Go to System Settings > Privacy & Security. Scroll down and see if there's a message about the app being blocked and click "Open Anyway" (you might need to unlock with your password),
- Using Terminal (for blocked apps):
  1. Open Terminal: Find it in Applications > Utilities.,
  2. Remove Quarantine: Type xattr -cr (note the space at the end) and then drag the problematic DMG file from Finder into the Terminal window to add its path, then press Enter.,
  3. Attach the DMG: Type hdiutil attach (space at the end), drag the DMG into Terminal, and press Enter.


---
### OSFR Launcher Source

**[Please check out the main github here](https://github.com/Open-Source-Free-Realms/Launcher)**.

### How to Contribute

**[Discord](https://discord.com/invite/qgVJ5Z7xEq)**
***
### Want to edit it's wineskin and wine directory?
1. Left click application
2. Select 'Show Package Contents'
3. Open 'Contents'
4. Run 'Wineskin' as a normal app (double click/open)
This will give you full access to things like winetricks, winecfg, etc. Also within 'Contents' folder you have access to the 'C' drive.
> **Note:** You will see a user folder with your mac user file name. This is autocreated when you frist open the app but it just a link that links into main user folder called 'Wineskin'
