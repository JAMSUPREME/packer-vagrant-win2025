# Shortcut pre-baked win images

At a glance, looking at using one of the following:
- https://portal.cloud.hashicorp.com/vagrant/discover/chocolatey/test-environment - should work?
- See other options here: https://portal.cloud.hashicorp.com/vagrant/discover?providers=virtualbox&query=windows%202025
- 

# Manual packer setup (TBD)

Stuff for packer and vagrant to run win 2025 on a mac against VirtualBox

Derived from https://github.com/ibeerens/packer/tree/main/vsphere/winsrv2025

# Running

Drop your ISO file into the top-level directory and run:
```
packer init .
packer build -force -only virtualbox-iso .\vbox-2016.json
```