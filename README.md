# Salt

# Raspberry Pi

## Keyboard
ibus-setup

## sudo raspi-config

* sudo raspi-config
* 2 Display Options
  * D3 VNC Resolution
* 3 Interface Options
  * I3 VNC
  * I5 I2C
* 5 Localisation Options
  * L1 Locale - sv_SE.UTF8
  * L2 Timezone - Europe - Stockholm
  * L3 Keyboard -
  * L4 WLAN Country - SE Sweden

## HatLabs
```
sudo apt update
sudo apt install pipx
sudo curl -L     https://raw.githubusercontent.com/hatlabs/SH-RPi-daemon/main/install-online.sh     | sudo bash
```
# Rut 200

## Setup 

* lan 192.168.11.11
* dhsp 192.168.11.100
* lease time infinite
* ssid Salt
* rms rms.teltonika-networks.com  15009

## Wireless

* general - country code - se
* SSID Salt

## Network - DHCP - Server Settings
* Range: 192.168.11.100 - 192.168.11.254

## Network - DHCP - Static Leases
* 192.168.11.111 lysmarine

## Network - DNS - General
* Inherited DNS servers - 192.168.1.1 - from - wan

## Status - Network - LAN - DHCP leases

* http://192.168.11.11/status/network/lan/ipv4
* http://192.168.11.11/network/dhcp_servers/static_leases/ipv4

# Linux
* sudo service NNNN stop

# Links
## OpenPlotter
* https://openmarine.net/
* https://forum.openmarine.net/index.php
* https://openplotter.readthedocs.io/latest/index.html
* https://github.com/openplotter
## OpenCpn
* https://www.thehowarths.net/cruising-information/technical-notes/546-kap-charts-and-opencpn
* https://openseamap.org/index.php?id=openseamap&no_cache=1&L=1
## SignalK
* https://signalk.org/specification/1.7.0/doc/index.html
* https://demo.signalk.org/documentation/modules.html
* https://demo.signalk.org/@signalk/freeboard-sk/assets/help/index.html#
* https://github.com/SignalK/freeboard-sk
* https://github.com/gregw/signalk-racer
## BBN
* https://bareboat-necessities.github.io/
* https://bareboat-necessities.github.io/my-bareboat/bareboat-os.html
* https://github.com/bareboat-necessities
* https://github.com/bareboat-necessities/bbn_compass
## HatLabs
* https://docs.hatlabs.fi/sh-rpi/docs/getting-started/
* https://docs.hatlabs.fi/sh-rpi/docs/add-ons/can_hat/
* https://docs.hatlabs.fi/sh-rpi/docs/add-ons/rs485_hat/
* https://www.waveshare.com/wiki/2-CH_RS485_HAT
## Apps
* https://www.zapfware.de/nmearemote/
##
* https://sailingpolars.com/
* http://jieter.github.io/orc-data/site/#NOR/NOR10750
* https://www.pbo.co.uk/reviews/boats/elan-31-the-elan-that-time-forgot
* 
