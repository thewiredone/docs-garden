---
{"dg-publish":true,"permalink":"/docs/spicetools/how-to-add-card-reader-and-add-cards-to-existing-asphyxia/"}
---

Card reader purchase link: https://www.amazon.com/dp/B0BVZQKGY9?psc=1&ref=ppx_yo2ov_dt_b_product_details 


1. The first thing to do is to open ACR122U v1.3 2012-6-8 and open Driver Installer.
    
    ![img01.png](/img/user/docs/img/cardreader/img01.png)
    
2. Open setup.exe and install the driver.
    
    ![img02.png](/img/user/docs/img/cardreader/img02.png)
    
3. Open contents folder for desired game and find then open spicecfg.
    
    ![img03.png](/img/user/docs/img/cardreader/img03.png)
    
4. Navigate to the Advanced tab.
    
    ![img04.png](/img/user/docs/img/cardreader/img04.png)
    
5. Enable HID SmartCard in the Advanced tab under the Card Readers section. Once done close spicecfg.exe
    
    ![img05.png](/img/user/docs/img/cardreader/img05.png)
    
6. Open Asphyxia-core.
    
    ![img06.png](/img/user/docs/img/cardreader/img06.png)
    
7. Once Asphyxia is running, we will need to capture the physical cards NFC number. To do this we must open the game. Open spice64.exe.
    
    ![img07.png](/img/user/docs/img/cardreader/img07.png)
    
8. When the game has loaded to at least the Konami screen, scan your card on the reader. After the card has been read and you’re greeted with the new player screen, close the game.
    
9. Open the log.txt file in your contents folder. Any card read by the reader while the game is open will post its NFC number in the log.
    
    ![img08.png](/img/user/docs/img/cardreader/img08.png)
    
10. CTRL+F to find: “read card:” as pictured and next to it you will find the NFC number. Copy this somewhere as we will be copying it into Asphyxia in a moment.
    
    ![img09.png](/img/user/docs/img/cardreader/img09.png)
    
11. Open your Asphyxia dashboard and go to the games plugin.
    
    ![img10.png](/img/user/docs/img/cardreader/img10.png)
    
12. Open the profiles section under the plugin.
    
    ![img11.png](/img/user/docs/img/cardreader/img11.png)
    
13. Find the profile that you would like to add the card to and take note of the ID listed.
    
    ![img12.png](/img/user/docs/img/cardreader/img12.png)
    
14. Click on Profiles under Dashboard.
    
    ![img13.png](/img/user/docs/img/cardreader/img13.png)
    
15. Find the ID from the Plugins/Profiles section and click the Edit symbol.
    
    ![img14.png](/img/user/docs/img/cardreader/img14.png)
    
16. Add the cards NFC number you found from the games log.txt file and then click the plus button next to it to add. Once added you will now see the physical card on the profile (with its access code too!).
    
    ![img15.png](/img/user/docs/img/cardreader/img15.png)
    

_**Note!**_

**To go further with this you’ll need something that can read/write “Felicia-lite-s” cards.**
