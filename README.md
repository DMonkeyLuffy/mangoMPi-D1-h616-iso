# mangoMPi-D1-h616-iso
Archivio personale iso attive


Estrarre il file dalla compressione "7z", e poi creare sd  (ex:"raspberry pi imager")

mangoMPi-D1: https://archive.org/download/armbian-22.08.0-trunk-nezha-jammy-current-5.19.0.7z/Armbian_22.08.0-trunk_Nezha_jammy_current_5.19.0.7z

mangoMPi-h616: https://archive.org/download/debian_bullseye_minimal_linux5.16.17_root_orangepi.img.7z/debian_bullseye_minimal_linux5.16.17_root_orangepi.img.7z


mangoMPi-D1:  per  wi-fi modifica file "armbian_first_run.txt.template"

#-----------------------------------------------------------------

.# Armbian first run configuration

.# Set optional end user configuration

.....

......

......

FR_net_use_static=1
FR_net_static_ip='192.168.1.xxx'     <<<< IP router
FR_net_static_mask='255.255.255.0'
FR_net_static_gateway='192.168.1.1'
FR_net_static_dns='192.168.1.1' #2 entries max, seperated by a space.

#-----------------------------------------------------------------

mangoMPi-h616:  per wi-fi
Per accesso: orangepi/orangepi

sudo nmcli device wifi connect YOURSSID password YOURPASS

