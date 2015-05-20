# buildtasks
TurnKey buildtasks
------------------

These scripts convert the ISOs that TKLDev produces into all of the different build types/formats.

Dependancies are stated within relevant scripts.

### `ovftool` 
(used by `bin/vm-bundle` for the VMDK & OVF builds)

**Note** `ovftool` is proprietary freeware and needs to be manually downloaded from VMware (download requires free VMware registration). Current version (as of 20 May 2015) is v4.1.0

https://my.vmware.com/group/vmware/get-download?downloadGroup=OVFTOOL410

Once downloaded from the internet (in your web browser) upload it to your TKLDev server and and install with:
````
/bin/sh VMware-ovftool-4.1.0-2459827-lin.x86_64.bundle
````

(obviously adjust version number as relevant)
