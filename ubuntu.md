
# Access a drive > 10 GB on a CloudPro Debian machine
* pvscan && vgextend localhost-vg /dev/sda3 && lvextend -l +100%FREE /dev/localhost-vg/root && resize2fs /dev/localhost-vg/root 
* https://www.reddit.com/r/CloudAtCost/comments/47ab1n/finally_figured_out_how_to_access_a_drive_10_gb/


# Add a sudoer

* adduser username
* usermod -aG sudo username
