# VMware Install Instructions

## How to install VMWare on Ubuntu based Systems

### Purpose
When you install VMWare Workstation PRO on a ubuntu based system you have issues when you try and run it.

Here are the steps to get it working:

1) Clone the repo `git clone https://github.com/nan0desu/vmware-host-modules.git`
2) `cd vmware-host-modules`
3) `git checkout workstation-17.5.2-k6.9+`
4) type `make`
5) type `sudo make install`




```
cd /tmp
sudo bash
git clone https://github.com/nan0desu/vmware-host-modules.git
cd vmware-host-modules
git checkout workstation-17.5.2-k6.9+
make
make install
```
