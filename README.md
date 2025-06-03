# WinDaq ExcelLink and UtilityPack Licensing Debug Tool

A special debug version Gauge.exe is used here to print out debug info to track down WinDaq ExcelLink and UtilityPack licensing errors

Instructions 
1. Rename gauge.exe in C:\Program Files (x86)\DATAQ Instruments\common to gauge_org.exe so that we can restore it after the test
2. Download the codes from this folder and extract a file call gauge.exe, which is in fact a debug tool under the same name in 1)
3. Copy the file gauge from step 2 to C:\Program Files (x86)\DATAQ Instruments\common
4. Run WinDaq Dashboard
5. Start WinDaq with the exact configuration you had trouble with ExcelLink or UtilityPack.  
6. Invoke WinDaq->View->Add ons...->Gauge and you should see the following report
7. ![alt text](https://www.dataq.com/resources/images/addondebug2.png)
8. The fourth item (Combined keys...)' bit 1 is ExcelLink, bit 2 is UtilityPack. For example, neither ExcelLink nor UtilityPack is available if this value is 0 or 1. Only ExcelLink is available if this value is 2 or 3. Only UtilityPac is available if this value is 4 or 5. Both ExcelLink and UtilityPack are available if this value is 6 or 7
9. The last item (WinDaq allows...) checks if ChannelStretch or Channel Configuration has any conflict with ExcelLink and UtilityPack Licensing. For example, if ChannelStretch is not actived in one of the device, this flag will be 0 when the device is included in channel expansion configuration. When this flag is zero, WinDaq will NOT allow recording, and some of the addons will not run.
10. Run Dashboard
11. Select a device that threw out WinDaq ExcelLink and UtilityPack errors. If the error is from ChannelStretch operation that involves multiple devices, select one at a time
12. Select Help->Device Info...
13. ![alt text](https://www.dataq.com/resources/images/addondebug3.png)
14. and you should see the following info, with unlock code, which shoulb be the SAME unlock code in your order. If not, install the unlock code per Step 17
15. ![alt text](https://www.dataq.com/resources/images/addondebug4.png)
16. If you don't see the unlock code, please download the latest WinDaq suite installation and try again
17. ![alt text](https://www.dataq.com/resources/images/addondebug5.png)
18. Repeat step 9-17 for ALL devices involved in the error
19. Send all images captured in above steps to Dataq Support for analysis
20. Once the problem is resolved, replace the debug version of gauge.exe with the original version renamed in step 1 so that you can use Gauge 

