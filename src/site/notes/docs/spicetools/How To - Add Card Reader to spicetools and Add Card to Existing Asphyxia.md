---
{"dg-publish":true,"permalink":"/docs/spicetools/how-to-add-card-reader-to-spicetools-and-add-card-to-existing-asphyxia/"}
---


1. The first thing to do is to open ACR122U v1.3 2012-6-8 and open Driver Installer.
    
    ![](file:///C:/Users/SMILE-MOBILE/Documents/iA%20Writer/img/cardreader/img01.png)
    
2. Open setup.exe and install the driver.
    
    ![](file:///C:/Users/SMILE-MOBILE/Documents/iA%20Writer/img/cardreader/img02.png)
    
3. Open contents folder for desired game and find then open spicecfg.
    
    ![](file:///C:/Users/SMILE-MOBILE/Documents/iA%20Writer/img/cardreader/img03.png)
    
4. Navigate to the Advanced tab.
    
    ![](file:///C:/Users/SMILE-MOBILE/Documents/iA%20Writer/img/cardreader/img04.png)
    
5. Enable HID SmartCard in the Advanced tab under the Card Readers section. Once done close spicecfg.exe
    
    ![](file:///C:/Users/SMILE-MOBILE/Documents/iA%20Writer/img/cardreader/img05.png)
    
6. Open Asphyxia-core.
    
    ![](file:///C:/Users/SMILE-MOBILE/Documents/iA%20Writer/img/cardreader/img06.png)
    
7. Once Asphyxia is running, we will need to capture the physical cards NFC number. To do this we must open the game. Open spice64.exe.
    
    ![](file:///C:/Users/SMILE-MOBILE/Documents/iA%20Writer/img/cardreader/img07.png)
    
8. When the game has loaded to at least the Konami screen, scan your card on the reader. After the card has been read and you’re greeted with the new player screen, close the game.
    
9. Open the log.txt file in your contents folder. Any card read by the reader will post its NFC number in the log.
    
    ![](file:///C:/Users/SMILE-MOBILE/Documents/iA%20Writer/img/cardreader/img08.png)
    
10. CTRL+F to find: “read card:” as pictured and next to it you will find the NFC number. Copy this somewhere as we will be copying it into Asphyxia in a moment.
    
    ![](file:///C:/Users/SMILE-MOBILE/Documents/iA%20Writer/img/cardreader/img09.png)
    
11. Open your Asphyxia dashboard and go to the games plugin.
    
    ![](file:///C:/Users/SMILE-MOBILE/Documents/iA%20Writer/img/cardreader/img10.png)
    
12. Open the profiles section under the plugin.
    
    ![](file:///C:/Users/SMILE-MOBILE/Documents/iA%20Writer/img/cardreader/img11.png)
    
13. Find the profile that you would like to add the card to and take note of the ID listed.
    
    ![](file:///C:/Users/SMILE-MOBILE/Documents/iA%20Writer/img/cardreader/img12.png)
    
14. Click on Profiles under Dashboard.
    
    ![](file:///C:/Users/SMILE-MOBILE/Documents/iA%20Writer/img/cardreader/img13.png)
    
15. Find the ID from the Plugins/Profiles section and click the Edit symbol.
    
    ![](file:///C:/Users/SMILE-MOBILE/Documents/iA%20Writer/img/cardreader/img14.png)
    
16. Add the cards NFC number you found from the games log.txt file and then click the plus button next to it to add. Once added you will now see the physical card on the profile (with its access code too!).
    
    ![](file:///C:/Users/SMILE-MOBILE/Documents/iA%20Writer/img/cardreader/img15.png)
    

_**Note!**_

_**To go further with this you’ll need something that can read/write “Felicia-lite-s” cards.**