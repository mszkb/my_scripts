# My RPI scripts

A collection of scripts and dotfiles that I use on my raspberry pi(s).

## Hardening script

Basic hardenings:
- ssh only elliptic curve
- remove unsecure ssh ciphers
- remove default user
- create some groups for pihole, apache and backup
- auto update
- ip address whitelisting
- user whitelisting

## Pihole install

Script that installs pihole with my defaults.
Secure DNS
Auto update

## Camera

crontab stuff that makes the camera create photos every 10 minutes
auto backups and uploads the files every hour
remove uploaded files
keeping track which files are already uploaded
