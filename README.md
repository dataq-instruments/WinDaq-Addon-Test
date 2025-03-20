# WinDaq/UtilityPack Test Version – Batch Add-on Startup Guide

This test version of WinDaq/UtilityPack allows for batch launching of WinDaq add-ons when starting WinDaq. For example, this feature enables WinDaq to automatically open multiple MagicMeters whenever it starts.

Setup Instructions 
1. Download and install this test version of WinDaq/UtilityPack
2. Run WinDaq and configure channels, gain, EU settings, etc. as needed.
3. Navigate to WinDaq → File → Save Default... to save your configuration.
4. ### Ensure your WinDaq configuration is finalized before proceeding.
5. Open each add-on you wish to include in the batch startup, configure its settings, and exit.
   - If multiple Gauge displays are needed for different channels, select each channel and open Gauge to save its configuration.
6. Run WinDaq and navigate to WinDaq → View → Add-on... → Add-on Batch Editor.<br/> 
![alt text](https://www.dataq.com/resources/images/addonbatch.png)
7. Repeat Steps 8-12 for each add-on you want to include in the batch startup
8. ![alt text](https://www.dataq.com/resources/images/add.BMP) Adds the selected add-on from the left panel to the batch operation
9. ![alt text](https://www.dataq.com/resources/images/minus.BMP) Removes a selected add-on from the right panel.
10. ![alt text](https://www.dataq.com/resources/images/config.bmp) Adjusts settings for the highlighted add-on in the right panel. 
    - Each add-on should have a unique index number, starting from 0.
    - By default, index numbers should align with the WinDaq channel indexes set in Step 3.
    - Example: If three analog channels are enabled in WinDaq and three Gauges were created, use index numbers 0 to 2 (a total of 3).
11. ![alt text](https://www.dataq.com/resources/images/testdrive.bmp) Runs a test of the selected add-on.
12. ![alt text](https://www.dataq.com/resources/images/accept.bmp) Saves the batch setup.
13. Exit WinDaq
14. Restart WinDaq - all selected add-ons from Step 8 will now launch automatically.

