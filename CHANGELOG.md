#

MiTool version 1.4.4:

- Device verification has been added in any mode, automatically restarting it to the appropriate mode

- A trial version for Flashing Fastboot Rom (v2) has been added (only for those facing issues with the following errors: "error: current device antirollback version is greater than this package" or "error: antirollback check error" or "Erase boot error")
Usage: run command: mitool t

- Improved handling of some errors automatically during bootloader unlocking, such as error code 10000, and more..

- delete the region selection request while unlocking the bootloader Let mitool take care of that

- Other improvements and additions

#

MiTool version 1.4.5:

- to facilitate the bootloader unlocking step:
  Now, when the browser is opened, you don't need to enter login credentials again; you only need to confirm login
(this improvement has been canceled due to some unexpected problems.)

- suggestions or issue reports can now be directly sent to t.me/Offici5l_Group through mitool. with command : m
(this is especially useful for users who do not have a telegram account.)

- other improvements.

#

MiTool version 1.4.6:

- Improve Flash-Fastboot-ROM and Fastboot-Flash-Rom-V2

- Other improvements

#

MiTool version 1.4.8 :

- add Bypass HyperOS BootLoader Restrictions

  bypass message "Cloudn't verify, wait a minute or two and try again" for miui and hyperos

- improvements

#

MiTool version 1.4.9 :

- Improvements:
It is now expected that the securityStatus16 error will not occur. If it does happen, please report it.

- Other improvements

#

MiTool version 1.5.0 :

- MiTool now directly utilizes MiUnlockTool for bootloader unlocking. If you only need to unlock the bootloader, you can use MiUnlockTool directly without MiTool.

- MiTool now directly utilizes MiBypassTool for bypassing. If you only need to bypass, you can use MiBypassTool directly without MiTool. (Changelog)

- Converted MiTool from mitool.sh to mitool.py.

- Removed many unnecessary features.

- (Some tools have been temporarily disabled.)

- Various improvements.

#

MiTool version 1.5.1 :

- Add MiAssistantTool version 1.0
Without unlocking the bootloader in recovery mode > Mi Assistant :
- Read-Info
- Check-ROM-Compatibility(With MD5)
- Flash-Official-Recovery-ROM

Update (1.5.1)
-Add Format-Data with (Mi Assistant)

#

MiTool version 1.5.2 :

- Add MiAssistantTool for arm & aarch64

#

MiTool version 1.5.3 :

- Fix installation for termux-adb ...
- Fix flashf "termux-api popup appears ! But the flashing process does not take start"

[

Miunlocktool version 1.5.2:
- Fix `"device is not recognized but termux-api popup appears !"`
- Improvements

]


[

MiAssistantTool version 1.1

- reboot (to system)
- Display the list of options before connecting the device
- Many fixes and improvements ...

]

- Add a step to verify that storage access(termux-setup-storage) is granted


[

Miunlocktool version 1.5.3:
- A global variable connect was added to track the device connection status. the code now checks for device connection only if it hasn't been connected yet, reducing redundant checks.
This will reduce the process time by about half, and it cannot be reduced further because the problem is with termux &termux-api itself.

- Add some messages to let the user know that the process is in progress.

]


[

Miunlocktool version 1.5.4:
- Edit the encryptData save path to be in /sdcard/encryptData Instead of being in /sdcard/Download/encryptData ( this will fix the issue :
FileNotFoundError: [Errno 2] No such file or directory: '/sdcard/Download/encryptData' )

]


[

Miunlocktool version 1.5.5:
- Other improvements can be found at : https://github.com/offici5l/MiUnlockTool/blob/main/CHANGELOG.md

]

#

MiTool version 1.5.4 :

- improvements




