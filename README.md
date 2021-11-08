# btrfs-rmdir
![alt text](https://raw.githubusercontent.com/unix1984/btrfs-rmdir/main/rmdir_example.png)


Delete more btrfs subvolume in a directory.


Install:
**wget -O /usr/local/sbin/btrfs-rmdir https://raw.githubusercontent.com/unix1984/btrfs-rmdir/main/btrfs-rmdir && chmod +x /usr/local/sbin/btrfs-rmdir**






*Example:
1) echo only: btrfs-rmdir -e /path/to/dir
2) delete!: btrfs-rmdir -d /path/to/dir

[-e] - echo only
[-d] - delete all subvolumes
[-h] - This help

