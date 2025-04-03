# WinDaq/UtilityPack Test Version – Add-on Auto Startup Guide

This test version of WinDaq/UtilityPack allows for batch launching of WinDaq add-ons when starting WinDaq. For example, this feature enables WinDaq to automatically open multiple MagicMeters whenever it starts.

Setup Instructions 
1. Download and install this test version of WinDaq/UtilityPack
2. Run WinDaq and configure channels, gain, EU settings, etc. as needed. For example, three channels are enabled
3. Navigate to WinDaq → File → Save Default... to save your configuration. 
4. ### Ensure your WinDaq configuration is finalized before proceeding.
5. Run WinDaq and navigate to WinDaq → View → Add-on... → !Add-on Auto Startup Config.<br/>![alt text](https://www.dataq.com/resources/images/addonbatch1.png)
 
6. Repeat Steps 8-12 for each add-on you want to include in the batch startup
7. ![alt text](https://www.dataq.com/resources/images/add.BMP) Adds the selected add-on from the left panel to the batch operation. Once an addon is added, assign an index number so that its configuration will be saved
    - Each add-on should have a unique index number, starting from 0.
    - By default, index numbers should align with the WinDaq channel indexes set in Step 2.
    - Example: If three analog channels are enabled in WinDaq and three MagicMeter were created, use index numbers 0 to 2, a total of 3, matching the total channel numbers in Step 2.
    - Once the configuration index is saved, the selected add-on will be launched for test drive, and you can setup accordingly

8. ![alt text](https://www.dataq.com/resources/images/minus.BMP) Removes a selected add-on from the right panel.
9. ![alt text](https://www.dataq.com/resources/images/accept.bmp) Saves the batch setup.
10. Exit then restart WinDaq - all selected add-ons from Auto Startup operation will now launch automatically. In the above example, three MagicMeters

