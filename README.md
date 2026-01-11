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

# Links
* https://docs.hatlabs.fi/sh-rpi/docs/getting-started/
* https://docs.hatlabs.fi/sh-rpi/docs/add-ons/can_hat/
* https://docs.hatlabs.fi/sh-rpi/docs/add-ons/rs485_hat/
* https://www.waveshare.com/wiki/2-CH_RS485_HAT
