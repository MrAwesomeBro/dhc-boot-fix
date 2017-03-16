# DHC Boot Fix

Script to fix a not running dhclient ob reboot on ubuntu servers after the hardware has been replaced around the hard disks.

### Usage

Clone the script to **/opt/***:

    git clone https://github.com/MrAwesomeBro/dhc-boot-fix.git

Then open your **/etc/rc.local** and insert this line:

    /opt/dhc-boot-fix/dhc_boot_fix
