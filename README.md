# Recommended way to install Ansible on various distributions:

## Debian 10

```sh
echo "deb http://deb.debian.org/debian buster-backports main" \
  > /etc/apt/sources.list.d/backports.list
apt update
apt -t buster-backports install ansible
```

## CentOS 7/8

```sh
yum install epel-release
yum install ansible
```


##  openSUSE 15

```sh
zypper install ansible
```

## Ubuntu 20.04 LTS

```sh
sudo apt-get update
sudo apt-get install ansible
```
