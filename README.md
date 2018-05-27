# pmd
# poor's man duma

A small script made for ASUS routers running Merlin firmware, which is trying to detect the current Activision server, retrieves geographical IP date and using Skynet ( https://github.com/Adamm00/IPSet_ASUS#help ) allows you to ban the server IP,IP range or the whole country (probable makes no sense, but i added this because i can).


## Prerequisites: 

- Asus router with Merlin Firmware installed (https://asuswrt.lostrealm.ca). Tested on latest release 384.5
- JFFS enabled


## Installation:

1. Download the script in /JFFS partition 
  (login, cd /jffs, wget https://raw.githubusercontent.com/sfortis/pmd/master/pmd.sh )
2. Give execution permissions ( chmod +x pmd.sh )
3. Edit the script and customize the variables / paths.
