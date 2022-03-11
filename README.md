# osbase-customization
This script customize a fresh installation for my own use.

## Usage
On a fresh centos/rhel/rocky/almalinux installation :
```shell
dnf install epel-release
dnf install ansible
ansible-playbook customize.yml
```

On a fresh debian/ubuntu installation :
```shell
apt install ansible
ansible-playbook customize.yml
```
