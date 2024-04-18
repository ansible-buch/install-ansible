# Recommended way to install an Ansible Community Package

## Debian 12/11

```sh
apt update
apt install ansible
```


## Rocky Linux 9/8

```sh
dnf install epel-release
dnf install ansible
```


##  openSUSE Leap 15

```sh
zypper install ansible
```

## Ubuntu 24.04/22.04 LTS

```sh
sudo apt update
sudo apt install ansible
```

<br/>

## Versions

If you choose the distribution package as described, you will get the
following version of Ansible:

| Distribution | Ansible Version |
|:---|---|
|Debian 12|7.3.0|
|Debian 11|2.10.8|
|Rocky 9|7.7.0|
|Rocky 8|8.3.0|
|openSUSE Leap 15|2.9.27|
|Ubuntu 24.04|9.2.0|
|Ubuntu 22.04|2.10.8|

On systems with outdated versions (such like openSUSE) you may prefer the
installation via Python PIP:

1. Install the `python3-pip` distribution package
2. `pip3 install ansible`

> Even this will not always get you the newest version, because newer Ansible
> versions require newer versions of Python!