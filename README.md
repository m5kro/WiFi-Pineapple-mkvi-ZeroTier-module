# WiFi-Pineapple-mkvi-ZeroTier-module
A module that installs and configures zerotier-one for the wifi pineapple nano and tetra. [Tested on os version 2.9.0](https://github.com/xchwarze/wifi-pineapple-cloner)

### Install

To install, place the ZeroTier folder in /pineapple/modules or /sd/modules and reboot.
Then at the web interface go to the ZeroTier module and install dependencies.
Once dependencies are installed reboot again.

### KNOWN ISSUES

kmod-tun always installs to internal due to issue with missing /dev/net/tun when installed in sd.

### Goals

Advanced config editing.

Fix known issues.

Show ip address on module page.

Get allowed/authenticated status.
