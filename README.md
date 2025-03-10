# libmspdb

## Description

![CI Tests](https://github.com/IntroVirt/libmspdb/actions/workflows/ccpp.yml/badge.svg)

**libmspdb** is a parsing library for Microsoft Program Database (PDB) files. This library is primarily used by [IntroVirt](https://github.com/IntroVirt/IntroVirt) to parse memory in Windows virtual machines. 

## Quick Start

### Install the latest release

libmspdb can be installed from prebuilt packages using the PPA for Ubuntu bionic and focal:
```
sudo add-apt-repository ppa:chpio/introvirt
sudo apt-get update
sudo apt-get install libmspdb-dev
```

## Build and install from source

To build from source:
```
sudo apt-get -y cmake libcurl4-openssl-dev libboost-dev git
git clone https://github.com/IntroVirt/libmspdb.git
cd libmspdb/build/
cmake ..
make -j
```

Debian packages can then be built and installed (recommended):
```
make package
sudo apt install ./*.deb
```

Or `make` can be used directly to install:
```
sudo make install
```

## Interested In Working For AIS?
Check out our [Can You Hack It?®](https://www.canyouhackit.com) challenge and test your skills! Submit your score to show us what you’ve got. We have offices across the country and offer competitive pay and outstanding benefits. Join a team that is not only committed to the future of cyberspace, but to our employee’s success as well.

<p align="center">
  <a href="https://www.ainfosec.com/">
    <img src="https://github.com/IntroVirt/IntroVirt/raw/main/.github/images/ais.png" alt="ais" height="100" />
  </a>
</p>
