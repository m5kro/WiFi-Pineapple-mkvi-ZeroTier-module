# WiFi-Pineapple-mkvi-ZeroTier-module
A module that installs and configures zerotier-one for the wifi pineapple nano and tetra.

### Install

To install, place the ZeroTier folder in /pineapple/modules or /sd/modules and reboot.
Then at the web interface go to the ZeroTier module and install dependencies.
Once dependencies are installed reboot again.

### KNOWN ISSUES

zerotier-one always installs to internal due to issue with uci not finding config when installed in sd.

kmod-tun always installs to internal due to issue with missing /dev/net/tun when installed in sd.

### Goals

Advanced config editing.

Fix known issues.

Show ip address on module page.

Get allowed/authenticated status.
