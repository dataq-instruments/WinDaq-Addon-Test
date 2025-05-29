# WinDaq ExcelLink and UtilityPack debug tool

A special version Gauge.exe is used here to print out debug info to track WinDaq ExcelLink and UtilityPack errors

Instructions 
1. Rename gauge.exe C:\Program Files (x86)\DATAQ Instruments\common to gauge_org.exe so that we can restore it after the test
2. Download the codes from this folder and extract a file call gauge.exe, which is in fact a debug tool under the same name in 1)
3. Copy the file gauge from step 2 to C:\Program Files (x86)\DATAQ Instruments\common
4. Run WinDaq Dashboard
5. Start WinDaq with the exact configuration you had trouble with ExcelLink or UtilityPack.  
6. Invoke WinDaq->View->Add ons...->Gauge and you should see the following report
7. ![alt text](https://www.dataq.com/resources/images/addondebug.png) 
8. Send this image to Dataq Support for analysis
9. Once the problem is resolved, replace the debug version of gauge.exe with the original version renamed in step 1 so that you can use Gauge 

