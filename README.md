# packer-vagrant-win2025

Stuff for packer and vagrant to run win 2025 on a mac against VirtualBox

Derived from https://github.com/ibeerens/packer/tree/main/vsphere/winsrv2025

# Running

Drop your ISO file into the top-level directory and run:
```
packer init .
packer build -force -only virtualbox-iso .\vbox-2016.json
```