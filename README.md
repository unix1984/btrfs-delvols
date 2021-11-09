# btrfs-delvols

![btrfs-delvols_example](https://raw.githubusercontent.com/unix1984/btrfs-delvols/main/btrfs-delvols_example.png)



Delete more btrfs subvolume in a directory.


Install:  
  
  method 1:
    
  **git clone https://github.com/unix1984/btrfs-delvols.git**
    
  **mv btrfs-delvols/btrfs-delvols /usr/local/sbin/btrfs-delvols**
    
  **chmod +x /usr/local/sbin/btrfs-delvols**
  
    
    
    
  method 2:
    
**wget -O /usr/local/sbin/btrfs-delvols https://raw.githubusercontent.com/unix1984/btrfs-delvols/main/btrfs-delvols && chmod +x /usr/local/sbin/btrfs-delvols**






*Example:
1) echo only: btrfs-delvols -e /path/to/dir
2) delete!: btrfs-delvols -d /path/to/dir

* [-e] - echo only
* [-d] - delete all subvolumes
* [-h] - This help



