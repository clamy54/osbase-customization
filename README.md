# osbase-customization
This script customize a fresh installation for my own use.

## Usage
On a fresh centos/rhel/rocky/almalinux installation :
```shell
dnf install -y epel-release git
dnf install -y ansible
ansible-playbook customize.yml
```

On a fresh debian/ubuntu installation :
```shell
apt install ansible
ansible-playbook customize.yml
```
