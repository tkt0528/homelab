# Architecture

## Current Environment

### Hypervisor

* Proxmox VE

### Production Containers

* 100 : Samba
* 101 : Kavita
* 102 : Jellyfin

### Storage

* ZFS
* External HDD mounted on /mnt/nas

### Network

* Proxmox Host:

  * 192.168.11.100:8006

* Samba:

  * 192.168.11.11

* Kavita:

  * 192.168.11.15:5000

* Jellyfin:

  * 192.168.11.18:8096
