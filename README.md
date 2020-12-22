# Mini Monkey - Hardware #

This repo has the PCB design data for the Mini-Monkey that is based upon the LPC55S69 in a VFBGA98 package.     Each PCB revision is in its own folder.  I typically always keep copies of all revisions in one repo so I can have access to multiple CCA versions at one time (instead of branches for each PCB/CCA).   Branches are used for development and merged into master when boards are sent out.

The Mini-Monkey is in a prototype state.   Use at your own risk.

### Latest Revision - Navigation ###

The latest revision is PCB Rev C. 

The design files are in Altium v20 format.

### History/Notes

#### PCB REV C:

- Added SD/eMMC Storage
- Fixed battery charger and added USB bypass.
- Accidentally used p-ch on backlight control.  Need to fix in future revision.



#### PCB REV B:

- Switched to using USB1 as the ROM bootloader is easier to use out of the box
- Fixed RST connection issue from REV A.
- There is now UART connections to the IO Pins.  Using the UART that also always for ISP Boot.
- Move the RST button to make ISP entry easier for humans
- Added some test points.

*Note:  there are still some issues with the battery/charger on REV B.  See the "bug" on the schematics.    It is usable but will be improved in the future.*


#### PCB Rev A:

- Included for historical purposes.  This is just an assembly test run @ MacroFab.  



