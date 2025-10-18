# Disabe Windows Copilot AI from Windows 10 and 11
* run gpedit-enabler.bat as admin
* Press Windows + R > type gpedit.msc and hit Enter
* Navigate to User Configuration > Administrative Templates > Windows Components > Windows Copilot
* Turn off Windows Copilot > Chose the enabled option (confusingly to "enable" the disable)

## sources
https://www.reddit.com/r/WindowsHelp/comments/1c1k1o9/disable_windows_copilot_ai_windows_10_and_11/
https://www.majorgeeks.com/files/details/add_gpedit_msc_with_powershell.html
https://github.com/Fleex255/PolicyPlus
