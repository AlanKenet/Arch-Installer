# Arch-BIOS-Installer
This is an edit of the arch installation script made by luca.py for BIOS systems.

All original lines that were changed have been marked as "Removed" and the changes have been marked as "Added" with respect to the original.

Notes:
* Enter the Timezone with format Zone/Subzone. Example: "[+]→ Enter the Timezone with format Zone/SubZone : America/Chicago"
* Enter the full path to the drive in the "[+]→ Enter The Drive :" option. To avoid problems when installing GRUB. Example: "[+]→ Enter The Drive : /dev/sda".

Changes:
* Removal of loadkeys for French distribution (keeping the default distribution).
* Added option to select timezone.
* Formatting and mounting for DOS partition table.
* Change the GRUB installation for BIOS systems.
* Minor correction in useradd commands to user creation.
* Added wheel group privilege especification to sudoers.
* Change in the timezone selection

All credits go to Luca.py from https://gitlab.com/luca.py/arch-installer
