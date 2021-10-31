# Recommended way to install Ansible

## Debian 11

```sh
apt update
apt install ansible
```

## Debian 10

```sh
echo "deb http://deb.debian.org/debian buster-backports main" \
  > /etc/apt/sources.list.d/backports.list
apt update
apt -t buster-backports install ansible
```

## Rocky Linux 8, CentOS 7/8

```sh
yum install epel-release
yum install ansible
```


##  openSUSE Leap 15

```sh
zypper install ansible
```

## Ubuntu 20.04 LTS

```sh
sudo apt-get update
sudo apt-get install ansible
```
