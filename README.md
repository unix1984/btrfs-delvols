# btrfs-delvols

![btrfs-delvols_example](https://raw.githubusercontent.com/unix1984/btrfs-delvols/main/btrfs-delvols_example.png)



Delete more btrfs subvolume in a directory.


Install:
**wget -O /usr/local/sbin/btrfs-delvols https://raw.githubusercontent.com/unix1984/btrfs-delvols/main/btrfs-delvols && chmod +x /usr/local/sbin/btrfs-delvols**






*Example:
1) echo only: btrfs-delvols -e /path/to/dir
2) delete!: btrfs-delvols -d /path/to/dir

* [-e] - echo only
* [-d] - delete all subvolumes
* [-h] - This help


<div id="donate-button-container">
<div id="donate-button"></div>
<script src="https://www.paypalobjects.com/donate/sdk/donate-sdk.js" charset="UTF-8"></script>
<script>
PayPal.Donation.Button({
env:'production',
hosted_button_id:'BABJM2XDMA256',
image: {
src:'https://www.paypalobjects.com/en_US/i/btn/btn_donate_SM.gif',
alt:'Donate with PayPal button',
title:'PayPal - The safer, easier way to pay online!',
}
}).render('#donate-button');
</script>
</div>
