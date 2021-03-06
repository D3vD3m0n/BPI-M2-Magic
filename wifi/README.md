# Wifi 802.11 b/g/n 2.4GHz (AP6212)

[BPI Series WiFi Firmware Compatible with BPI M1-Plus/ M2/ M2Plus/ M3 WiFi Firmware](https://github.com/BPI-SINOVOIP/BPI_WiFi_Firmware)

<img src="https://raw.githubusercontent.com/D3vD3m0n/BPI-M2-Magic/master/images/wirelessantennatypes.jpg?alt=media" href="https://github.com/D3vD3m0n/BPI-M2-Magic/tree/master/wifi/" class="image-12799b3c" style="cursor: zoom-in;">
<h3><span class="mw-headline" id="WiFi_Client">WiFi Client</span></h3>
<p><b>You have two ways to setup WiFi Client</b>
</p><p>1. Use commands to setup WiFi client
</p>
<ul><li> ip link set wlan0 up</li>
<li> iw dev wlan0 scan | grep SSID</li>
<li> vim /etc/wpasupplicant/wpa_supplicant.conf </li></ul>
<pre>
country=DE
ctrl_interface=DIR=/var/run/wpa_supplicant GROUP=netdev
update_config=1

 network={    
 ssid="ssid"    
 psk="password"    
 priority=1 
 }
</pre>
<ul><li> wpa_supplicant -iwlan0 -c /etc/wpa_supplicant/wpa_supplicant.conf</li>
<li> dhclient wlan0</li></ul>
<p>2. Use UI interface to setup WiFi Client
</p>
<h3><span class="mw-headline" id="StartX">StartX</span></h3>
<ul><li> apt-get install xorg</li>
<li> apt-get install xserver-xorg</li>
<li> apt-get install xinit</li></ul>
<p><a rel="nofollow" class="external free" href="https://askubuntu.com/questions/518454/what-does-startx-command-do">what-does-startx-command</a>
</p>

<div Class="reset-3c756112--wholePageSticky-f53dafd2"><div class="reset-3c756112--pageContainer-3ec6d8d0"><div class="reset-3c756112"><div class="reset-3c756112--pageHeader-15724735"><div class="reset-3c756112--pageHeaderInner-7c0f0284"><div class="reset-3c756112--pageHeaderWrapperContent-6897c946"><div class="reset-3c756112--horizontalFlex-5a0077e0"><div class="reset-3c756112--pageHeaderIntro-0c1463da"><h1 class="reset-3c756112--pageTitle-33dc39a3"><span class="text-4505230f--DisplayH900-bfb998fa--textContentFamily-49a318e1">BPI-M2 Magic wifi antenna slot</span></h1></div><div style="grid-template-columns: repeat(1, auto);" class="reset-3c756112--toolbar-a6a9f7d2--medium-8e46b02c--pageHeaderToolbar-6457a802--withControlsClosed-3e96e46c"></div></div><div class="reset-3c756112--pageHeaderDescription-22970244"></div></div></div></div><div class="reset-3c756112--toaster-c029690e"></div><div class="reset-3c756112--pageBody-a91db4ac"><div data-editioncontainer="true" class="reset-3c756112--container-960c7c26"><div data-slate-editor="true" data-key="1e86c0d4341e45f1885f03a68327a789" autocorrect="on" spellcheck="true" data-gramm="false" style="outline: currentcolor none medium; white-space: pre-wrap; overflow-wrap: break-word;"><p class="blockParagraph-544a408c" data-key="1e9840e5c1a34a899398a42db89367f7"><span class="text-4505230f--TextH400-3033861f--textContentFamily-49a318e1"><span data-key="78fe7422e38c4e2091c8d485cad59cce"><span data-offset-key="78fe7422e38c4e2091c8d485cad59cce:0">banana pi BPI-M2 Magic have support ap6212 wifi&amp;BT module onboard</span></span></span></p><p class="blockParagraph-544a408c" data-key="6e9f0dbcd87b4b9ca175028f2c6f9508"><span class="text-4505230f--TextH400-3033861f--textContentFamily-49a318e1"><span data-key="01d9da4226cb404c97253afcaaf4a988"><span data-offset-key="01d9da4226cb404c97253afcaaf4a988:0">BPI-M2 Magic have wifi antenna slot on board</span></span></span></p><p class="blockParagraph-544a408c" data-key="f21eea4fbf7a48a7ae8098e8fe16e738"><span class="text-4505230f--TextH400-3033861f--textContentFamily-49a318e1"><span data-key="979ec875f4584a2a8b00be7401d6df3f"><span data-offset-key="979ec875f4584a2a8b00be7401d6df3f:0">if you want use a extend antenna for bpi-, you can add by youself.</span></span></span></p><p class="blockParagraph-544a408c" data-key="b465906e773b42568d38dbf37d130c3b"><span class="text-4505230f--TextH400-3033861f--textContentFamily-49a318e1"><span data-key="de9fcb6da99f4ac3a59892493b411540"><span data-offset-key="de9fcb6da99f4ac3a59892493b411540:0">wifi extend antenna slot:</span></span></span></p>
<div class="reset-3c756112--figureAlignCenter-2d9bf702">
<div class="reset-3c756112--figureLayer-b6ab7c94"><img tabindex="0" src="https://gblobscdn.gitbook.com/assets%2F-M2HWtQZi70-rAX2he34%2F-M2HWuQWfmMDDcGnCw7t%2F-M2HXFx_kLc9AIfDULes%2Fwifi%20slot.jpg?alt=media" class="image-52799b3c" style="cursor: zoom-in;"></div></div>
