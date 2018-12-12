# packer_alicloud_ubuntu_sample
Packer and Ansible will make Alicloud Ubuntu Golden Image.

# How to make your image
1. cd builder
2. packer build -var-file=variables.json packer.json
