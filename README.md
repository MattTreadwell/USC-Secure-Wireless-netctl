<p align="center">
  <img src="https://assets-www.calm.com/2e77697f538befb44e5e9a40f5775d2a.png" width="50%">
</p>

# USC Secure Wireless netctl and iwd config

These configs help with connecting to USC Secure Wifi on unix systems

## Netctl

* Replace `eth0` with the wireless interface you will be using
* For username and password, use your USC email credentials omitting the ` @usc.edu` 
* Place `USC_Secure_Wireless` in `/etc/netctl/`

## IWD (use with networkd)

* Setup systemd-networkd to work with your wireless interface
* For username and password, use your USC email credentials omitting the ` @usc.edu` 
* Place `USC_Secure_Wireless.8021x` in `/var/lib/iwd`
