# linux-wifi
Overview of WiFi USB adapters for Linux

See also: https://github.com/mendel5/linux-bluetooth

## Important links
- https://github.com/morrownr/USB-WiFi
- https://github.com/morrownr/USB-WiFi/blob/main/The_Short_List.md
- https://github.com/morrownr/USB-WiFi/blob/main/USB_Chipsets.md
- https://github.com/morrownr/USB-WiFi/blob/main/Kali_Linux_Recommended_Adapters.md
- https://github.com/morrownr/USB-WiFi/blob/main/Recommended_WiFi_Router_Settings.md

### Questions
- What about Qualcomm? `The main reason for the limited support is that there are only 2 companies supplying chipsets for USB Wifi adapters - Mediatek and Realtek.`
- What about Broadcom?
- Are `Qualcomm QCA9377-7` and `mt7662u` supported?
- Is TP-LINK TL-WN823N v2 with `RTL8192EU` supported? (compared to v1 with `RTL8192CU`)
- Letztendlich alle Geräte von Amazon.de testen (Suche und Topseller)

## TP-Link links
- https://www.amazon.de/dp/B07M69276N/ TP-Link Archer T3U
- https://www.amazon.de/dp/B0859M539M/ TP-Link Archer T3U Plus
- https://www.amazon.de/dp/B0088TKTY2/ TP-Link TL-WN823N
- https://www.tp-link.com/de/home-networking/all-adapter/?filterby=4884%2C4809
- https://www.tp-link.com/en/home-networking/all-adapter/?filterby=6093%7C4809%7C4927
- http://en.techinfodepot.shoutwiki.com/wiki/TP-LINK_Archer_T2U_Nano
- http://en.techinfodepot.shoutwiki.com/wiki/TP-LINK_Archer_T2U_Plus
- http://en.techinfodepot.shoutwiki.com/wiki/TP-LINK_Archer_T3U
- http://en.techinfodepot.shoutwiki.com/wiki/TP-LINK_Archer_T3U_Plus
- http://en.techinfodepot.shoutwiki.com/wiki/TP-LINK_TL-WN823N_v1
- http://en.techinfodepot.shoutwiki.com/wiki/TP-LINK_TL-WN823N_v2
- https://deviwiki.com/wiki/TP-LINK_Archer_T3U
- https://deviwiki.com/wiki/TP-LINK_Archer_T3U_Plus
- https://wikidevi.wi-cat.ru/TP-LINK_Archer_T3U
- https://wikidevi.wi-cat.ru/TP-LINK_Archer_T3U_Plus
- https://geizhals.de/tp-link-archer-t3u-ac1300-archer-t3u-a2083565.html
- https://geizhals.de/tp-link-archer-t3u-plus-ac1300-archer-t3u-plus-a2291212.html
- https://wiki.ubuntuusers.de/WLAN/Karten/TP-Link/
- https://forum.ubuntuusers.de/topic/treiber-fuer-wifi-stick-tp-link-archer-t3u-rtl/
- https://wiki.ubuntuusers.de/WLAN/Karten/
- https://forum.ubuntuusers.de/topic/treiber-fuer-wifi-stick-tp-link-archer-t3u-rtl/
- https://www.club.computerwissen.de/qa/86756-tp-link-archer-t3u-unter-linux
- https://community.tp-link.com/en/home/forum/topic/248212
- https://community.tp-link.com/en/home/forum/topic/277278
- https://community.tp-link.com/en/home/forum/topic/208022
- https://www.computerbase.de/forum/threads/archer-t3u-treiber-auf-linux-mint-19-3-installieren.1927445/
- https://askubuntu.com/questions/1134101/tp-link-archer-t3u-not-working-in-ubuntu-18-04
- https://github.com/morrownr/88x2bu
- https://linustechtips.com/topic/1312520-where-can-i-get-drivers-for-tp-link-archer-t3u-for-linux/
- https://forums.linuxmint.com/viewtopic.php?t=306556
- https://www.gutefrage.net/frage/archer-t3u-treiber-auf-linux-mint-installieren
- https://unix.stackexchange.com/questions/692658/how-to-install-driver-archer-t3u-plus-for-linux-20-04-ac1300
- https://gist.github.com/julianlam/0ce7692ca10fb91970b6693bc02587ce
- https://linux-hardware.org/?id=usb:2357-012d
- https://old.reddit.com/r/linux/comments/5p38ry/what_prevents_realtek_wireless_drivers_from_being/
- https://old.reddit.com/r/linuxhardware/comments/9tsx1m/whats_the_best_driver_for_realtek_wifi_in_linux/
- https://old.reddit.com/r/linux/comments/38vwbf/the_state_of_wifi_drivers_just_bad_luck/
- https://old.reddit.com/r/linuxquestions/comments/qbcjn2/are_realtek_and_nvidia_the_only_brands_i_need_to/

## Other links
- https://www.amazon.de/gp/bestsellers/computers/430156031/
- https://forum.openwrt.org/t/what-wifi-5ghz-ac-should-i-look-for-when-shopping-qualcomm-atheros-closed-source-broadcom-is-not-recommend-thx/106553

```
sudo lshw -C network
```
Source:
- https://askubuntu.com/questions/333424/how-can-i-check-the-information-of-currently-installed-wifi-drivers

```
sudo lsusb
```

## AVM links
- https://avm.de/produkte/fritzwlan/fritzwlan-stick-ac-430-mu-mimo/
- https://avm.de/produkte/fritzwlan/fritzwlan-stick-ac-860/
- https://geizhals.de/avm-fritz-wlan-usb-stick-ac-430-mu-mimo-20002766-a1669615.html
- https://geizhals.de/avm-fritz-wlan-usb-stick-ac-860-20002687-20002724-a1082383.html
- https://debianforum.de/forum/viewtopic.php?t=167735
- https://wiki.ubuntuusers.de/WLAN/Karten/AVM/

## Chipsets
- Suche: `"chipset" OR "chipsatz"`
- AVM FRITZ!WLAN USB Stick AC 430 MU-MIMO: Qualcomm `QCA9377-7`
- AVM FRITZ!WLAN USB Stick AC 860: Ralink `mt7662u`
- TP-Link Archer T2U Nano: `Realtek RTL8811AU`
- TP-Link Archer T2U: Realtek `RTL8811AU`
- TP-Link Archer T3U: Realtek `RTL8812BU`
- TP-Link Archer T3U Plus: Realtek `RTL8812BU`
- TP-Link TL-WN722N: Atheros `AR9002U`
- TP-Link TL-WN725N: Realtek `RTL8188EUS`
- TP-Link TL-WN821N: Realtek `RTL8192EU`
- TP-Link TL-WN823N: Realtek `RTL8192EU`
- CSL 1: Ralink `RT5572`
  - https://www.amazon.de/dp/B00LLIOT34
- CSL 2: Realtek `RTL8812BU`
  - https://www.amazon.de/dp/B07KS66YBF
- CSL 3: Realtek `RTL8812AU`
  - https://www.amazon.de/dp/B01M67XBJ4
- Netgear A6210: `?`
