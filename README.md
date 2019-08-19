# HuaweiUpdater
A small tool for updating Huawei/Honor phones

https://forum.xda-developers.com/honor-view-10/development/tool-huaweiupdater-update-to-emui-9-t3884904
I made a tool to "force update" my phone (Honor View 10, European/C432 model), and I thought I'd share it in case anybody wants to give it a try.

Notes
It is Windows-only (Specifically Windows 10 (64-bit), build 1809, although it probably works fine for most/all other versions of Windows)
It requires .NET Framework to be installed on your computer. It can be downloaded from here
It might cause some anti-virus programs to flag it due to the nature of the tool (although nothing on VirusTotal detects it as malware)
Currently, a lot of stuff is hard-coded (source code available below), including the path to HiSuite.exe. If the path to your HiSuite installation isn't "C:\Program Files (x86)\HiSuite\HiSuite.exe" (or "C:\Program Files\HiSuite\HiSuite.exe" in the case of 32-bit Windows), the tool won't work
It's currently only supposed to work with the BKL-L09 (C432) model. Do not use this tool if you do not have the BKL-L09 (C432) model
If you are on 32-bit Windows (your HiSuite installation path is "C:\Program Files\HiSuite" instead of "C:\Program Files (x86)\HiSuite"), download the HuaweiUpdaterWin32.7z file. Otherwise, download the regular HuaweiUpdater.7z file

And, of course, please use the tool at your own risk. I'm not responsible if the update somehow ends up breaking your phone.

Usage
Connect your phone to your computer through USB
Before proceeding, make sure HiSuite isn't running. Open Task Manager (Ctrl+Alt+Del -> Task Manager or Ctrl+Shift+Escape) and make sure "Huawei PC Suite" (hisuite.exe) isn't running. If it's running, right-click and select "End Task" to kill the process
Run "Launcher.exe" and HiSuite should open
Click on the "Update" button. There should be a red dot on it
Wait for HiSuite to finish installing the update on your phone

Source code can be found here: https://github.com/Smaehtin/HuaweiUpdater
