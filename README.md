Expedition 1 installer for Ubuntu 22.04 (Jammy)
This script downloads Palo Alto’s latest **expedition1_Installer_latest.tgz**, unpacks it, and installs all dependencies on Ubuntu 22.04.

This requires a fresh install of Ubuntu 22.04.  After installing Ubuntu, please run

```bash
sudo -i
apt update && apt upgrade -y
```
**Usage**

```bash
curl -O https://raw.githubusercontent.com/utahman3431/pan-expedition-installer/main/initSetup.sh
chmod +x initSetup.sh
sudo ./initSetup.sh
```
