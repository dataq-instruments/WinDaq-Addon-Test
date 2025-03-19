# WinDaq UtilityPack

This is the test version of WinDaq/UtilityPack, to allow batch starting of WinDaq addons when starting WinDaq

To do that, 
1. Please download and install the above installation
2. Go to C:\windows and editor to open TPDATAQ.INI
3. Locate [Tools] section
4. Locate a section that looks like the following:5. 
  F4=C:\Program Files (x86)\DATAQ Instruments\common\addonstartmanager.exe 
  TEXT4=REMOVED 
  ALTTEXT4=!Add-on Batch Editor 
6. Modify it to 
  F4=C:\Program Files (x86)\DATAQ Instruments\common\addonstartmanager.exe 
  TEXT4=!Add-on Batch Editor 
  ALTTEXT4=!Add-on Batch Editor 
7. Save TPDATAQ.INI
8. Run WinDaq and invoke WinDaq->View->Add on...->Add-on Batch Editor
9. Add whatever add ons you wish to be included in the batch operation
10. Save it
11. Exit WinDaq
12. Restart WinDaq and you will see all the addons selected in Step 8 start up autmotically

