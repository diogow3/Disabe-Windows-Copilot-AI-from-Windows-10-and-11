# Disabe Windows Copilot AI and Telemetry from Windows 10 and 11

## Disable Copilot
1. run gpedit-enabler.bat as admin
2. windows + r > gpedit.msc
3. User Configuration > Administrative Templates > Windows Components > Windows Copilot
4. Turn off Windows Copilot > Chose the enabled option ("enable" the option to the disable copilot)

## Disable forced telemetry
1. windows + r > services.msc
2. double click "User Experience and Telemetry"
3. startup type > disable

## sources
* https://www.reddit.com/r/WindowsHelp/comments/1c1k1o9/disable_windows_copilot_ai_windows_10_and_11/
* https://www.majorgeeks.com/files/details/add_gpedit_msc_with_powershell.html
* https://github.com/Fleex255/PolicyPlus
