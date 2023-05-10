# Make-MMI3G-acios_db.ini
H-B MMI3G SD script to create acios_db.ini from the installed PKG file info

This H-B MMI3G SD script generates a valid acios_db.ini file from the installed navigation database components in /mnt/nav/pkgdb.  It assumes that no acios_db.ini file is found in /HBpersistance/navi/db.

To apply, extract the attached ZIP archive to an empty FAT32 SD card.  Start the MMI3G system and wait for all functions to start fully (at least 3 minutes).  Insert the script SD card into an open SD slot.  Follow the screen prompts.  Eject the SD card after it finishes.  Inspect the plain-text LOG file for errors.  The new acios_db.ini file will be saved in the var dir/folder of the SD card.

The script can be applied on H-B MMI3G (HNav), MMI3GP (HN+) and RNS-850 (HN+) systems.
