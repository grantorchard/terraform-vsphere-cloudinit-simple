# Cloud-Init Sample

This repo provides an example of deploying a Ubuntu machine with some hardcoded values in both the metadata and userdata files included in the templates directory.

Cloud-init configuration is provided via the [VMware guestinfo datasource](https://github.com/vmware/cloud-init-vmware-guestinfo). A sample Packer build that has the relevant dependencies pre-installed can be found [here](https://github.com/grantorchard/packer-vsphere-cloudinit).