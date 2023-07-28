# SNAP NAME Snap
This repository contains the packaging metadata for creating a snap of SNAP NAME built from the SOURCE. For more information on snaps, visit [snapcraft.io](https://snapcraft.io/). 

## Installing the Snap
The snap can be installed directly from the Snap Store. Follow the link below for more information.
<br>

[![Get it from the Snap Store](https://snapcraft.io/static/images/badges/en/snap-store-black.svg)](https://snapcraft.io/<snap-name>)

## Building the Snap
### Clone Repository
```bash
git clone https://github.com/canonical/<snap-name>-snap.git
cd <snap-name>-snap
```
### Installing and Configuring Prerequisites
```bash
sudo snap install snapcraft --classic
sudo snap install lxd
sudo lxd init --auto
```
### Packing and Installing the Snap
```bash
snapcraft pack
sudo snap install ./<snap-name>*.snap --devmode
```

## License
The SNAP NAME Snap is free software, distributed under the Apache
Software License, version 2.0. See
[LICENSE](https://github.com/canonical/<snap-name>-snap/blob/<branch>/LICENSE)
for more information.

## Trademark Notice
<!-- Fill if relevant -->

