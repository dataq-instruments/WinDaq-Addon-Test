# WinDaq UtilityPack

This is the test version of WinDaq/UtilityPack, to allow batch starting of WinDaq addons when starting WinDaq. For example, WinDaq can spawn multiple MagicMeters whenever it starts with this feature

To do that, 
1. Please download and install this version of WinDaq/UtilityPack
2. Run WinDaq and configure channels/gain/EU settings, etc
3. Invoke WinDaq->File->Save Default... 
4. # Finalize WinDaq configuration before proceeding
5. Invoke each addon you wish to use in batch operation, set up its configuration and exit. If you need multiple Gauge displays for multiple channels, highlight each channel and invoke Gauge to save its configuration
6. Run WinDaq and invoke WinDaq->View->Add on...->Add-on Batch Editor<br/> 
![alt text](https://www.dataq.com/resources/images/addonbatch.png)
7. Repeat Step 5-8 to add all the addons you wish to include in the batch operation
8. ![alt text](https://www.dataq.com/resources/images/add.BMP) push this button to add the selected addon from the left panel in the batch operation,
9. ![alt text](https://www.dataq.com/resources/images/minus.BMP) push this button to remove a selected addon from the right panel
10. ![alt text](https://www.dataq.com/resources/images/config.bmp) push this button to config the addon highlighted on right panel, each each one should have a different index number, starting from 0. By default, the index number should match the index channels of WinDaq configuration created in Step 3. For example, if you have 3 analog channels enabled on WinDaq and created 3 Gauges in Step 3, you could use index 0 to 2, total 3
11. ![alt text](https://www.dataq.com/resources/images/testdrive.bmp) push this button to test drive the addon highlighted in right panel if needed
12. ![alt text](https://www.dataq.com/resources/images/accept.bmp) push this button to save the batch set up
13. Exit WinDaq
14. Restart WinDaq and you will see all the addons selected in Step 8 start up autmotically

