# HomeLab-docs
Ideas and docs for my home lab

## Hardware
Minisforums MS-01 i9 13th, 4x4TB NVME SSD, 96GB RAM 

## Virtualisation
Proxmox - I would like to swap this for NixOS eventually but don't know enough about linux virtualisation

### Disk setup
4TB to Proxmox for VMS
2x4TB to NAS for mutable storage

## VMs
### PFSense
#### OS
PFSense

### NAS
#### OS
NixOS
#### Specs
20GB from Proxmos for OS

2x4TB NVME SSDs for storage

4 cores

8GB RAM
#### Software
Samba
#### Shares
2TB - Photos - Used to store photos I take - need some kind of software to manage them

250GB - Game servers - Attached to each game server and run from this drive

2TB - Media - Jellyfin/plex server

250GB - Share - attached to each VM and PC as a way to transfer files

### Minecraft
#### OS
NixOS

### Media
#### OS
NixOS

### Photo
#### OS
NixOS
