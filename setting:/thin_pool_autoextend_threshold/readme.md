```
sudo lvcreate -V30G -T $vg/$pool -n Ubuntu
  WARNING: Sum of all thin volume sizes (250.00 GiB) exceeds the size of thin pool ubuntu-vg/stor-thin and the size of whole volume group (235.42 GiB).
  WARNING: You have not turned on protection against thin pools running out of space.
  WARNING: Set activation/thin_pool_autoextend_threshold below 100 to trigger automatic extension of thin pools before they get full.
  Logical volume "Ubuntu" created.
```
