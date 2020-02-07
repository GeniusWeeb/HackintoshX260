# HackintoshX260
Lenovo X260 I5-6300U runnins macOs  10.14.6


Update : successfully updates to macOs catalina , no external 32bit wifi usb working as support curbed from Apple.
Solution : Get a Dw1560 wifi card or BCM 94352 , depending on your wifi slot  i.e A type or E type.


Intel Hd 520



Skylake processors

Contains the whole clover folder with a custom boot theme

Contains plist for the intel hd520 devices

Contains the custom patched DSDT required for battery managemenet in Lenovox260(Dual Battery or Single Batery)

No dual to single Battery integration patches , I suggest you use Intel Power gadget or CocounutBattery

Enables Battery status 

Contains SSDT-PNLF for brightness fix but can also be patched with the Rehabman Brightness fix patche at his repo with Maciasl

Contains CpuFriend kext for optimizing battey levels at idle state (800hz) so to consume less battery, i didnt see much change though. 



NOTE:
This plist will not work if you have changed any parts of your laptop, ram and ssd changes are allowed.

Changes to any other part and i strongly recommend Clover Acpi Hotpatch (which even i havent put efforts into yet)

which the basically allows to change content wihout having to tinker your DSDT .

NOTE:
Cases of Lenovo and other laptop manufacturers , whitelisting comonents to make them not compatible with the respective laptops have been seen, but tis a thing of past,
--LenovoX260 doesnt have a whitelist , so as for this device you sdnt face much issues
