Linksys WRT1900AC (OpenWRT + ShadowSocks + ChinaDns + polarssl v1.3.4)
=======
An OpenWRT project for the Linksys WRT1900AC router
-------

**Base OpenWRT from fork of Belkin Mamba Tag v3.9**
https://github.com/jimmychungbelkin/Mamba

###ipk download:

[chinadns v1.1.7](https://github.com/cooerson/Mamba/releases/download/v3.9-polarssl/ChinaDNS-C_1.1.7_armadaxp.ipk)
[libpolarssl v1.3.4](https://github.com/cooerson/Mamba/releases/download/v3.9-polarssl/libpolarssl_1.3.4-1_armadaxp.ipk).
[ShadowSocks-libve v1.4.8](https://github.com/cooerson/Mamba/releases/download/v3.9-polarssl/shadowsocks-libev-polarssl_1.4.8_armadaxp.ipk).

###img download:

[openwrt-armadaxp--jffs2-128k.img](https://github.com/cooerson/Mamba/releases/download/v3.9-polarssl/openwrt-armadaxp--jffs2-128k.img)

-

**How to update from Belkin/Linksys UI**

1. Login to WRT1900AC local UI
2. Navigate to the Connectivity tab
3. Select Manual firmware update
4. Select image to load (e.g., openwrt-armadaxp--jffs2-128k.img)
5. Select Update firmware

After the firmware is updated, the unit will reboot, and the default ip address will be 192.168.200.1. 
The default SSID's will be MAMBA_2G4, and MAMBA_5G2, password is 'belkin123'.
The default username for OpwnWrt is 'root', and there is no default password set.
The unit will ask you to set a default password after you login to the UI.

-

**How to update from OpenWrt to Belkin/Linksys**

1. Login to the WRT1900AC web UI
2. Select the 'System' Tab, and then 'Backup / Flash Firmware' tab
3. In the 'Flash new firmware image' section click the 'choose file' button and select your firmware
4. Click 'flash image'

-
