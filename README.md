# lmv
## Домашнее задание
### Уменьшить том под / до 8G
1. ![alt text](./hwpic/1%208G.png)
2. ``` ls /mnt ```
3. ``` for i in /proc/ /sys/ /dev/ /run/ /boot/; do mount --bind $i /mnt/$i; done ```
4. ``` chroot /mnt/ ```
5. ``` grub2-mkconfig -o /boot/grub2/grub.cfg ```
6. в файле **/boot/grub2/grub.cfg** заменить **rd.lvm.lv=VolGroup00/LogVol00** на **rd.lvm.lv=vg_root/lv_root**
7. ![alt text](./hwpic/1lsblk.png)

