# Arch-Installer

This is a modified version of the arch installation script created by luca.py for BIOS legacy systems.

All original lines that have been altered are marked as "Removed" and the changes made are marked as "Added".

Notes:

* Enter the timezone using the format Zone/Subzone. Example: "[+]→ Enter the Timezone with format Zone/SubZone : America/Chicago"
* To avoid issues with GRUB installation, specify the full path to the drive in the "[+]→ Enter The Drive :" option. Example: "[+]→ Enter The Drive : /dev/sda".
* FLAG file contain a "to fix" list.

Instructions:

* From the Arch installation medium terminal, run curl to copy the arch-install file and save it as installer.
* Execute the installer file using the sh command.
* Follow the steps inside the script
* After reboot, execute the continue file with the sh command.
* Enjoy!

Changes:

* The loadkeys for the French distribution has been removed, keeping the default distribution.
* A select timezone option has been added.
* Formatting and mounting for a DOS partition table.
* Change in the GRUB installation method for BIOS legacy systems.
* Minor corrections to the useradd commands for user creation.
* The wheel group privileges have been specified in the sudoers file.
* Timezone selection has been modified.
* Git package added before reboot system.
* Sddi installation has been removed.
* Yay installation has been fixed.
* Minor corrections to the pacman parameters.

All credits go to Luca.py from https://gitlab.com/luca.py/arch-installer
