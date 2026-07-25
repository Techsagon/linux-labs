# Rocky Linux Repository Management And Recovery

## Overview

A Rocky Linux server began reporting duplicate repository definitions for BaseOS, AppStream, EPEL, CRB, and multiple optional repositories. This server was configured to use repos local to the region because of internet censorship, The problem arised after the server was updated and installed official repos all over again.

## Objectives

- Backup the current repositories directory
- Remove all repositories
- Rebuild official Rocky repositories
- Configure an Iran based mirror as a fallback repository
- Configure RPM GPG key verification
- Add Epel
- Validate package metadata and installation
- Confirm no duplicate repository warnings remain

## Technologies

- VMWare Workstation
- Rocky Linux 9.8 (Blue Onyx)
- download.rockylinux.org
- MobaXterm

## Lessons Learned

- "dnf makecache" caches metadata
- How to manually configure linux repositories
- How to manually download and implement GPG keys
