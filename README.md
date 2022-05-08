# marlin-x8
Marlin 1.1.5 with TronXY X8 configuration 

This is Marlin 1.1.5 vanilla firmware with custom configuration to make it work for TronXY X8.
I kept the original setting of the tronxy x8, with the only difference that the language is set to italian.
Customize Configuration.h and Configuration_adv.h for your setup.

Note:
Configured to make it work with CXY-V.2 board(thanks to siliconzoo).
I just made the LCD display work.

# Arduino

## Board installation
Here's how to install Sanguino:

* File > Preferences
* To the "Additional Boards Manager URLs" field, add https://raw.githubusercontent.com/Lauszus/Sanguino/master/package_lauszus_sanguino_index.json 180. If you have multiple URLs in the field, separate them with commas.
* Click the "OK" button.
* Tools > Board > Boards Manager
* Wait for the downloads to finish.
* Search for "sanguino".
* Click on "Sanguino by Kristian Sloth Lauszus".
* Click the "Install" button.
* Wait for the installation to finish.
* Click the "Close" button.
* You will now see a Tools > Board > Sanguino menu item.

## Needed Libraries

* U8glib
