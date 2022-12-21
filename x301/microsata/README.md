untested, unprinted, I dont even remember if I finalized it

slots into microsata drive bay
provides 2242 m.2 (sata) interface for ssd
rest of space used for SD card and USB3.0 type A port
Requires separate daughter pcb which goes in WLAN slot (not made yet)
2242 m.2 should be fully functional as is. 

requires removal of steel plate between ssd slot and keyboard
requires wlan relocation to wwan slot
wlan relocation requires cutting RFKILL trace on either the card or the wwan port
daughter pcb will have provision to breakout RFKILL and status leds to then solder to WWAN
probably an adapter will be made to install into WWAN and convert to m.2, with provisions for rfkill and status leds so that no cutting is needed.
FFC ribbon exits between bottom case and pcb into ram compartment, then bends 90 degrees to go to wlan port.

future version with two usb type-c instead of type A featuring:
PD charging (probably only 20v)
USB 3.0 (shared bandwidth) 
DisplayPort via displaylink chip, possibly dual port with aux mode. Uses WUSB slot with second pci-e 2.0 to usb board
displayports /should/ ignore arbritrary limits and the laptop will be able to drive up to 4 displays.

possibly a 3d printable hdd cover with the needed slots, or just cut your own. 