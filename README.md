<center><img src='logo.png' /></center>
<br />
SnapVPN is the technology (software and hardware) that allows one to watch straight from a smartTV any content from a different country when abroad...It is a small device (portable and low energy consumption) that creates a wifi Access Point where to connect your devices (e.g. smart tv, laptop, tablet and forth); the <b>snapvpn client device</b> will internally create a vpn towards another device (either a windows computer, a VPN router or <b>snapvpn server device</b>) and it redirects all requests from the wifi AP to that vpn overcoming the geo-localisation check. The snapvpn devices are easy to use thanks to a mobile application available on the major store and don't require any special technical skill (just plug-and-play configuration!).
What you need is a <b>snapvpn client image</b> (download for free!), a valid account, if required, to login to your preferred provider (for example DAZN or NetFlix) and a <b>snapvpn server device</b> (or windows computer, router with vpn capability) located in the country where you'd like to grab content from (your family or friend's place).
<br/><br/>
Application's capabilities:<br/>
-> Changing Access Point name and password for your wifi AP extender<br/>
-> Changing settings for connecting towards a server device (decide if to start the connection at boot of the snapvpn device)<br/>
-> Manage different snapvpn boxes (yes! you can have multiple boxes each of them connected to several countries!)<br/>
-> <b>Enable/disable on the fly which device has to go through which country</b><br/>
-> Start/Stop of a vpn on demand<br/><br/>

Benefit:<br/>
-> Cheap solution (total cost for a <b>snapvpn client device</b> is roughly 20~60 euro)<br/>
-> Extremely low power consumption<br/>
-> Extend your WIFI in a place not reached by your router<br/>
-> Having access to the local network of the VPN (not for <b>snapvpn server device</b> that runs completely isolated)<br/>
-> No installation is required on your devices (smartwatch, smartphone, smartTV, tablet and so on) to access to a different country's content<br/>
-> No limit on the number of devices connected to the VPN (because the box will abstract the same connection for any device)<br/>
-> <b>Use native applications (like DAZN) and remote controller on your smartTV </b><br/>
-> No hassle to configure and get it up and running (plug-in the <b>snap client device</b> and configure it using the mobile application!)<br/>
-> when you are done, you can always use it as small pc or something else by just change the SD card that is powering the snapvpn device!<br/>
-> Build your private shared <b>snapvpn server device</b>'s network amongst your friends or family
<br/><br/>
Technical details:<br/>
-> SnapVPN box works with protocol PPTP thus that is the protocol required on the server side<br/>
-> PPTP is not as secure as other vpn technologies, thus don't share your server to the world :)<br/>
-> In case of windows vpn server or <b>snapvpn server device</b>, port 1723 on the router needs to be opened and redirected towards the server device<br/>
<br/><br/>

What you need:<br/>
-> Download a SnapVPN image: <a href='https://drive.google.com/open?id=196KClAFhz91l7rSFFBuPCqS_97YSTjaU'>BananaPI</a> or <a href='https://drive.google.com/open?id=1L5MGNqU8nsyhB1sZ_wa7JHbFKxuX5f2a'>Raspberry</a><br/>
-> A micro or standard SD with at least 4GB (class 10): e.g <a href='https://www.amazon.it/Kingston-SDCS-16GBSP-Velocit%C3%A0-Adattatore/dp/B079H19HLM/ref=sr_1_17_sspa?s=electronics&ie=UTF8&qid=1544287527&sr=1-17-spons&keywords=micro+sd&psc=1'/>micro sd</a><br/>
-> A BananaPI M1 or raspberry PI 3 (also model B+): e.g. <a href='https://www.reichelt.com/ch/en/raspberry-pi-3-b-4x-1-4-ghz-1-gb-ram-wlan-bt-raspberry-pi-3b-p217696.html?GROUPID=8242&START=0&OFFSET=16&&r=1'>raspberry</a><br/>
-> A WIFI dongle (<b>Edimax EW-7811UTC</b>) - <b>only if you plan to use a BananaPI: <a href='https://www.amazon.it/Edimax-EW-7811UTC-Scheda-di-rete/dp/B00FW6T36Y/ref=sr_1_1?ie=UTF8&qid=1544289254&sr=8-1&keywords=Edimax+EW-7811UTC'>wifi dongle</a></b><br/>
-> A power supply 5V - 2A (BananaPI) or 3A (raspberry): e.g. <a href='https://www.amazon.it/NorthPada-Raspberry-Alimentatore-Caricabatterie-Interruttore/dp/B01N33JS4A/ref=sr_1_5?s=electronics&ie=UTF8&qid=1544288116&sr=1-5&keywords=alimentatore+5v+2.5a'>power supply</a><br/>
-> A RJ45 ethernet cable<br/>
-> A SD writer device<br/>
<br />
Bundle are available as well: <a href='https://fr.aliexpress.com/item/New-Original-UK-Raspberry-Pi-3-Mod-le-B-Kit-Cas-16-32g-SD-Carte-3A/32878678366.html?spm=a2g0w.search0104.3.51.38de38692l1M24&ws_ab_test=searchweb0_0%2Csearchweb201602_1_10065_10068_319_317_10696_453_10084_454_10083_10618_10307_10821_538_537_10302_536_10134_10059_10884_10887_100031_321_322_10103%2Csearchweb201603_51%2CppcSwitch_0&algo_pvid=4e94373b-7155-4ecc-a8cd-8292f828b7ed&algo_expid=4e94373b-7155-4ecc-a8cd-8292f828b7ed-7'>raspberry bundle</a><br/><br/>

How to proceed:
1. Write snapvpn image on the micro sd using <a href='https://sourceforge.net/projects/win32diskimager/'>win32diskimager</a>
2. Plug the micro sd in the box, attach the ethernet cable on the box and the wall
3. Plug-in the power supply in the socket
4. Wait until <b>SNAP_VPN</b> wifi AP is visible
5. Connect with your smartphone using <b>EnjoyVPN</b> default password
6. The new wifi AP you've just connected to auto configures itself to use your network and share your internet connection!
7. Download and install SnapVpn application for <a href='https://play.google.com/store/apps/details?id=com.snapvpn'>android</a> or apple
8. Launch it
9. <b>Change the wifi AP's default password to the one you like most</b>
10. You are ready to configure and start enjoying your blocked content on smart tv or other devices!
<br/><br/>
Have fun!


