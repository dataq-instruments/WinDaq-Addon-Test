# WinDaq ExcelLink and UtilityPack debug tool

A special debug version Gauge.exe is used here to print out debug info to track down WinDaq ExcelLink and UtilityPack errors

Instructions 
1. Rename gauge.exe in C:\Program Files (x86)\DATAQ Instruments\common to gauge_org.exe so that we can restore it after the test
2. Download the codes from this folder and extract a file call gauge.exe, which is in fact a debug tool under the same name in 1)
3. Copy the file gauge from step 2 to C:\Program Files (x86)\DATAQ Instruments\common
4. Run WinDaq Dashboard
5. Start WinDaq with the exact configuration you had trouble with ExcelLink or UtilityPack.  
6. Invoke WinDaq->View->Add ons...->Gauge and you should see the following report
7. ![alt text](https://www.dataq.com/resources/images/addondebug2.png)
8. Run Dashboard
9. Select a device that threw out WinDaq ExcelLink and UtilityPack errors. If the error is from ChannelStretch operation that involves multiple devices, select one at a time
10. Select Help->Device Info...
11. ![alt text](https://www.dataq.com/resources/images/addondebug3.png)
12. and you should see the following info, with unlock code. If you don't see the unlock code, please download the latest WinDaq suite installation and try again
13. ![alt text](https://www.dataq.com/resources/images/addondebug4.png)
14. Repeat step 9-13 for ALL devices involved in the error
15. Send all images captured in above steps to Dataq Support for analysis
16. Once the problem is resolved, replace the debug version of gauge.exe with the original version renamed in step 1 so that you can use Gauge 

