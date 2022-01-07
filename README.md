## Reboot into grub
`reboot-into-grub` provide a simple selection cli to reboot into your desired grub entry directly, without having to manually reboot and select the entry from grub menu.

**Installation**:
-   Edit the `/etc/default/grub` file and replace `GRUB_DEFAULT=0` with `GRUB_DEFAULT=saved`
-   `> sudo update-grub`
- `> git clone https://github.com/jkmpariab/reboot-into-grub.git`
- `> cd reboot-into-grub/`
- `> ./reboot-into-grub`
```
> reboot-into-grub
Choose the entry to reboot into:
0. Ubuntu
1. Advanced options for Ubuntu
2. Windows Boot Manager (on /dev/sda1)
3. UEFI Firmware Settings
input: 0
rebooting into "Ubuntu"...
```