Launch Bootcamp Partition From Virtual Box Directly.
----------------------------------------------------

Usage
=====

- Install Virtual Box First,
- Create a configure file at `~/.bootcamprc`:

```
BOOTCAMP="BOOTCAMP"                     # Your Bootcamp partition's label
VMDIR="/Users/username/VirtualBox VMs"  # Where you want to save Bootcamp vm files
```

- Run `bootcamp` and wait.

If you run bootcamp first time, it will prepare disk image and vm for a while. After that, VM will be launched automatically.

After first time, it will launch VM directly.

When running VM, it will unmount your Bootcamp partition. If you want to mount the partition again, run:

```
> bootcamp mount
```

Enjoy it.