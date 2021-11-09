# btrfs-delvols

![btrfs-delvols_example](https://raw.githubusercontent.com/unix1984/btrfs-delvols/main/btrfs-delvols_example.png)



Delete more btrfs subvolume in a directory.

<mark style="background-color: lightblue">Marked text</mark>

Install:  
  
    
  **git clone https://github.com/unix1984/btrfs-delvols.git**
    
  **mv btrfs-delvols/btrfs-delvols /usr/local/sbin/btrfs-delvols**
    
  **chmod +x /usr/local/sbin/btrfs-delvols**
 


*Example:
1) echo only: btrfs-delvols -e /path/to/dir
2) delete!: btrfs-delvols -d /path/to/dir

* [-e] - echo only
* [-d] - delete all subvolumes
* [-h] - This help



