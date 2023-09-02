# [NEW UVMOD in Portuguese](https://uvmod.meshtastic.pt/)

# QuanSheng_UV-K5 Firmwares for UV-K5, UV-K5(8), UV-K6 & UV-R5 Plus

[QuanSheng UV-K5 Firmwares](https://github.com/spm81/Quansheng_UV-K5/tree/main/Firmware/UV-K5)<br>
[QuanSheng UV-R5 Plus Firmwares](https://github.com/spm81/Quansheng_UV-K5/tree/main/Firmware/UV-5R%20Plus)<br>
[QuanSheng UV-K6 Firmwares](https://github.com/spm81/Quansheng_UV-K5/tree/main/Firmware/UV-K6)


# You have a QuanSheng UV-K6 or UV-R5 Plus and you get this error ???
![Screenshot](https://raw.githubusercontent.com/spm81/Quansheng_UV-K5/main/photos/fwerror.jpg)

You are in the right place !!! :) <br>
You can find more help on [QuanSheng UV-K5 Telegram Group](https://t.me/quansheng_uvk5_en) (English Only)<br><br>
Podes-me encontrar no [Telegram](https://t.me/PMR446PT) (Portuguese Only) !!!<br><br>

# Explanation of differences between product types
FCC ID : XBPUV-K5<br>
Model Number: UV-K5, UV-K5(2), UV-K5(6), UV-K5(8), UV-K5(9), UV-K5(11),
UV-K5(22), UV-K5(66), UV-K5(88), UV-K5(99), UV-5R, UV-5R PLUS, UV-82<br>
To Whom It May Concern:<br>
We, The QUANSHENG ELECTRONICS CO., LTD. hereby declare that the models are
identical except the model names & cover designs.
https://fcc.report/FCC-ID/XBPUV-K5/6401581.pdf

#FCC Report <br>
https://fccid.io/XBPUV-K5



# Firmware version spoofing modded firmware v2 for v3, v4 uv-5r plus

1. Download file qsfirm.py place it into the same folder with k5_v2.01.26_mod.bin

2. Run command: `qsfirm.py unpack k5_v2.01.26_mod.bin fw.dec.bin fw.ver.bin`

4. Edit file fw.ver.bin in hex editor find 2 and change it to start with 4, for example 4.00.1 instead of 2...

5. Run command: `qsfirm.py pack fw.dec.bin fw.ver.bin k5_v2.01.26_mod_v4.bin`
