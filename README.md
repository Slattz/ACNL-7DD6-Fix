# ACNL-7DD6-Fix

## About
* This program fixes a game crashing error in ACNL.
* The error seems to be influenced by Rydog's NTR Plugin.
* The error is caused by an invalid building (0x19) in the list.
* This program fixes the invalid 0x19 building, aswell as other invalid buildings.
* Checksum code from ACRehash by WulfyStylez (Original Author) & WemI0 (Welcome Amiibo Updated).

## How To Tell If My Save Has This Error
* Firstly, your game will crash when starting the game.
* Secondly, it's likely you will only ever get this crash if you use / have used Rydog's NTR Plugin 4.0 Beta 3 before.
* If you have Luma3DS CFW:

    * When your game crashes, you'll usually get the "**An exception occured**" onscreen.
    * This crash report has lots of numbers and text.
    * On the top screen, there should be R0, R1, R2, R3, R4, etc listed.
    * This tool will only fix crashes that have `00007DD6` in **R1**.
        
* If you haven't Luma3DS CFW:

  * Open your `garden_plus.dat` save in [Marc Robledo's save editor](http://www.marcrobledo.com/acnl-editor/)
  * If there is a building beginning with `0x` followed by a number (e.g. **0x19**) in the list of buildings, your save **is** affected by this crash. This tool will fix the invalid building(s) in the save.
