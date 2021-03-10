# Openwrt v19.07.5 for Orange Pi Zero board

MicroSD image file in 'zip' file
Configuration file in 'config.opiz' file
Installed modules in 'manifest' file

- LAN static 192.168.1.1, DHCP enable.
- WiFi access point brigded with LAN. SSID "Opiz", no password.
- Support L2TP, PPPoE.
- LEDs: green=power, red=LTE_tx|rx
- Support ndis, ras, cdc, ncm modems (Quectel EC21/EC25/EP06, SimCom SIM7600E-H, Sierra EM7455, Huawei E3372/ME90X, FoxConn TW77WXXX/Telit LN9X0/HP LT4X20+ etc)
- Support various USB-to-Eth converters.
- Support USB flash and USB HDD with ext4, exFat, vfat filesystems.
- Added multiwan3 with load balancing, Wireguard, Adblock, Tor, DNS over HTTPS, DynDNS, Luci (en, ru)
- Added smstool, atinout, modeminfo, modemmanager for modems setup.
