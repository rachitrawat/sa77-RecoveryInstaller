Recovery-Installer
==================

Your warranty may be void.
The developer cannot be held responsible for any damage done to device.

Recovey installer for locked bootloader. Compatible with Windows/Linux/Mac.

Uses e2fsck as hijack binary.

Requirements:
1. Rooted Phone
2. 15.3.A.0.26 or above firmware

Changelog:

v1.0
* Initial release

v1.1
* changed from sa77 to a e2fsck hijack

v1.2
* updated CWM to 6.0.4.8

v1.4
* UI enhancements
* Now supports menu using do while
1. Install cwm 6.0.4.8
2. Install some other recovery
3. Uninstall recovery
4. exit
* remove unnecessary delay in booting cwm
* switch to one time cyan LED
* Vibrator now triggers if keycheck is detected
* code cleanup

v1.5 : Hot update
* Fix screen shift issue completely
* Update CWM recovery
* philz recovery added as an option
* Open xda thread option in shell script too
* TWRP WIP

v1.6 
* Fix URLs
* Unclutter code
* Remove unecessary delay during boot
* battery improvements

v1.7
* Update cwm to 6.0.5.0
* Update adb drivers
* script improvements for shell 

v1.8
* Add TWRP 
* use exec instead of chroot (which broke TWRP earlier)
* Code cleanup & optimizations
