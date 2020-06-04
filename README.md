# Banana PI BPI-M2 Magic (BPi-M2M) Expansions 
[![Solid00](https://lh4.googleusercontent.com/proxy/5RbrUVcLsk1djbP9EK_A_KBPlkSWcG4_NmJSBMR94e21Es4xop9swuXtD-q1o0VVROJiAfkyS8vlyOv0hjcNRVZEMO5C_c6KI5cv-gHwqdUCrovrIDtEwQSOTSsiYUt3yYObugXWymqtDDXeTnRaoSkCbPRKz7f4)](https://github.com/D3vD3m0n/)| 

Kali Linux 2020.x Banana PI BPI-M2 Magic (BPi-M2M) Expansions 

     git BPI-M2-Magic

sudo rm -rf BPI-M2-Magic
sudo git clone https://github.com/D3vD3m0n/BPI-M2-Magic.git
sudo chmod -R 755 BPI-M2-Magic
cd BPI-M2-Magic/
configure:
sudo ./configure
sudo make
sudo make install

     Install BPI-M2-Magic via curl Install BPI-M2-Magic via wget 

$ sh -c "$(curl -fsSL https://raw.github.com/D3vD3m0n/BPI-M2-Magic/master/tools/install.sh)"

# BPI-M2 Magic hardware

Banana Pi BPI-M2 Magic can use A33 and R16 chip on board, and Allwinner A33 and R16 chip is PIN to PIN cmpatibility other spec is same.
+ 1 BPI-M2 Magic :Allwinner A33 onboard ,without eMMC flash onboard .
+ 2 BPI-M2 Magic Plus: Allwinner R16 onboard with 8G eMMC flash onboard.

[![Solid01](./images/overview.jpg)](https://github.com/D3vD3m0n/)[![Solid06](./images/overviewpins.jpg)](https://github.com/D3vD3m0n/)


<div class="reset-3c756112"><div class="reset-3c756112--pageHeader-15724735"><div class="reset-3c756112--pageHeaderInner-7c0f0284"><div class="reset-3c756112--pageHeaderWrapperContent-6897c946"><div class="reset-3c756112--horizontalFlex-5a0077e0"><div class="reset-3c756112--pageHeaderIntro-0c1463da"><h1 class="reset-3c756112--pageTitle-33dc39a3"><span class="text-4505230f--DisplayH900-bfb998fa--textContentFamily-49a318e1">BPI-M2 Magic hardware spec</span></h1></div><div style="grid-template-columns: repeat(1, auto);" class="reset-3c756112--toolbar-a6a9f7d2--medium-8e46b02c--pageHeaderToolbar-6457a802--withControlsClosed-3e96e46c"></div></div><div class="reset-3c756112--pageHeaderDescription-22970244"></div></div></div></div><div class="reset-3c756112--toaster-c029690e"></div><div class="reset-3c756112--pageBody-a91db4ac"><div data-editioncontainer="true" class="reset-3c756112--container-960c7c26"><div data-slate-editor="true" data-key="df1df7f3ce6f46dab9a210ad956b4bb6" autocorrect="on" spellcheck="true" data-gramm="false" style="outline: currentcolor none medium; white-space: pre-wrap; overflow-wrap: break-word;"><div class="reset-3c756112--tableWrapper-4a5ed20c"><div class="reset-3c756112--tableScroll-09f7c92d"><table class="table-0f56c2d8" data-key="6dba3133d3d843cdbd72c9d32b179ebf"><tbody><tr class="tableRow-41a0302b" data-key="a373b43df3f646188ed782721b75a5ab"><td data-table="cell" class="tableCell-150ac604" style="text-align: left;" data-key="385ca7825e1f4510bc165bba30c6bba2"><p class="blockParagraph-544a408c--noMargin-acdf7afa" data-key="f79054bdc6464b4d9f2886f485e6ea5d"><span class="text-4505230f--UIH400-4e41e82a--textContentFamily-49a318e1"><span data-key="42e4c503f9ec484f994b443c166bd23d"><span data-offset-key="42e4c503f9ec484f994b443c166bd23d:0">Soc</span></span></span></p></td><td data-table="cell" class="tableCell-150ac604" style="text-align: left;" data-key="e66d9f2573e648d597edc8fb33282eb5"><p class="blockParagraph-544a408c--noMargin-acdf7afa" data-key="d9de16e0e785475f8b952c9112fb645b"><span class="text-4505230f--UIH400-4e41e82a--textContentFamily-49a318e1"><span data-key="de5361aa8d994e1d940bab06513d3720"><span data-offset-key="de5361aa8d994e1d940bab06513d3720:0">Allwinner R16,Quad-code ARM Cortex-A7，also support A33 design</span></span></span></p></td></tr><tr class="tableRow-41a0302b" data-key="f0d6e64ddd7f435787aef0a464d76e39"><td data-table="cell" class="tableCell-150ac604" style="text-align: left;" data-key="f903e0d1b0f447d28d79adb98081f1b8"><p class="blockParagraph-544a408c--noMargin-acdf7afa" data-key="17c36748bcd045a9866ba859f7ca327f"><span class="text-4505230f--TextH400-3033861f--textContentFamily-49a318e1"><span data-key="980bbdbf6ecd4b5c8b6e50cdfceddb17"><span data-offset-key="980bbdbf6ecd4b5c8b6e50cdfceddb17:0">GPU</span></span></span></p></td><td data-table="cell" class="tableCell-150ac604" style="text-align: left;" data-key="c02f6a410e5f40af98a1a4741ecf02a1"><p class="blockParagraph-544a408c--noMargin-acdf7afa" data-key="199be03e26174fee8a503e362fe35832"><span class="text-4505230f--TextH400-3033861f--textContentFamily-49a318e1"><span data-key="f1f20e1622414f9abe154ce22385624c"><span data-offset-key="f1f20e1622414f9abe154ce22385624c:0">Mali 400 MP2</span></span></span></p></td></tr><tr class="tableRow-41a0302b" data-key="8d3f11cdf1884b2e8dbef759377f2905"><td data-table="cell" class="tableCell-150ac604" style="text-align: left;" data-key="55f82448908f496dade51a91e4be689c"><p class="blockParagraph-544a408c--noMargin-acdf7afa" data-key="756149a9e119415da68bdec87c4dd574"><span class="text-4505230f--TextH400-3033861f--textContentFamily-49a318e1"><span data-key="2b64e5eb8c144d7490cf1b862b44d9d1"><span data-offset-key="2b64e5eb8c144d7490cf1b862b44d9d1:0">SDRAM</span></span></span></p></td><td data-table="cell" class="tableCell-150ac604" style="text-align: left;" data-key="aa7cf8c66b4f41f0b0f80e884820b281"><p class="blockParagraph-544a408c--noMargin-acdf7afa" data-key="236e3874bb4546ffba83984a379ad0dc"><span class="text-4505230f--TextH400-3033861f--textContentFamily-49a318e1"><span data-key="50a28ee8558e473ebfa2cc267662be5a"><span data-offset-key="50a28ee8558e473ebfa2cc267662be5a:0">512MB DDR3 (shared with GPU)</span></span></span></p></td></tr><tr class="tableRow-41a0302b" data-key="ac6435d3a7b845d0a26bf47f3a330b37"><td data-table="cell" class="tableCell-150ac604" style="text-align: left;" data-key="92cbc775a7ab4cf2bbb95cc4a54bf2c1"><p class="blockParagraph-544a408c--noMargin-acdf7afa" data-key="4aa368a862504624a2baf97970639e65"><span class="text-4505230f--TextH400-3033861f--textContentFamily-49a318e1"><span data-key="1c456e978af54613b14f7bd0e9e19721"><span data-offset-key="1c456e978af54613b14f7bd0e9e19721:0">Power</span></span></span></p></td><td data-table="cell" class="tableCell-150ac604" style="text-align: left;" data-key="b960f722164a4f44bc08bc90d50489c5"><p class="blockParagraph-544a408c--noMargin-acdf7afa" data-key="074a69a45a7f494aa75f4ae491f61d64"><span class="text-4505230f--TextH400-3033861f--textContentFamily-49a318e1"><span data-key="e8d0d09dfbe244c4b7ed8bf3b569bbd5"><span data-offset-key="e8d0d09dfbe244c4b7ed8bf3b569bbd5:0">5V @ 2A via DC power</span></span></span></p></td></tr><tr class="tableRow-41a0302b" data-key="3e32c34857ea40e5b4dc6527e021f8a2"><td data-table="cell" class="tableCell-150ac604" style="text-align: left;" data-key="4877771eab054e1fa9e9206d43d6ecc5"><p class="blockParagraph-544a408c--noMargin-acdf7afa" data-key="338da96d82f84c789a02b2df2c4b687e"><span class="text-4505230f--TextH400-3033861f--textContentFamily-49a318e1"><span data-key="9fa6c676b3f540b998414f9ff0db1a11"><span data-offset-key="9fa6c676b3f540b998414f9ff0db1a11:0">Low-level peripherals</span></span></span></p></td><td data-table="cell" class="tableCell-150ac604" style="text-align: left;" data-key="2ec977be02c047779f5b772215ce3579"><p class="blockParagraph-544a408c--noMargin-acdf7afa" data-key="127ae2ac72f64ec1bbd14cad9ff3d18e"><span class="text-4505230f--TextH400-3033861f--textContentFamily-49a318e1"><span data-key="da93bdf88b364979be05d6e03ebb62e4"><span data-offset-key="da93bdf88b364979be05d6e03ebb62e4:0">40 Pins Header, 28×GPIO, some of which can be used for specific functions including UART, I2C, SPI, PWM.</span></span></span></p></td></tr><tr class="tableRow-41a0302b" data-key="a07950a1c60d47fe9327a05f5c971116"><td data-table="cell" class="tableCell-150ac604" style="text-align: left;" data-key="7d0828c7a9ba4d49a81dfb718c9a6d00"><p class="blockParagraph-544a408c--noMargin-acdf7afa" data-key="06133c78aeda41bdb44e2268170ae6ba"><span class="text-4505230f--TextH400-3033861f--textContentFamily-49a318e1"><span data-key="c3bcc39cb51849968c10c7491f919941"><span data-offset-key="c3bcc39cb51849968c10c7491f919941:0">Wifi</span></span></span></p></td><td data-table="cell" class="tableCell-150ac604" style="text-align: left;" data-key="8759c436a4994737b33502019abf830d"><p class="blockParagraph-544a408c--noMargin-acdf7afa" data-key="ea6938c7d9ea42cc881cc830f29b0647"><span class="text-4505230f--TextH400-3033861f--textContentFamily-49a318e1"><span data-key="74062184f2884e1d9df0afcb92a43d13"><span data-offset-key="74062184f2884e1d9df0afcb92a43d13:0">Wifi 802.11 b/g/n 2.4GHz (AP6212)</span></span></span></p></td></tr><tr class="tableRow-41a0302b" data-key="239a6aea378043aab5e64c2906118b6d"><td data-table="cell" class="tableCell-150ac604" style="text-align: left;" data-key="6445d71ade444661828a8c848c7cfb19"><p class="blockParagraph-544a408c--noMargin-acdf7afa" data-key="52aeb049f54d43919ee4debbf13d06c1"><span class="text-4505230f--TextH400-3033861f--textContentFamily-49a318e1"><span data-key="4b6851aa60d147e4b4b98ff8c8a5cc67"><span data-offset-key="4b6851aa60d147e4b4b98ff8c8a5cc67:0">Bluetooth</span></span></span></p></td><td data-table="cell" class="tableCell-150ac604" style="text-align: left;" data-key="7937801fb27842d0b9d4c9112dae48ef"><p class="blockParagraph-544a408c--noMargin-acdf7afa" data-key="a7f9c26d2dfc4ad4a1ea154bcbd14c7a"><span class="text-4505230f--TextH400-3033861f--textContentFamily-49a318e1"><span data-key="7271cbc8a91545ed8ccc098e85bcdc04"><span data-offset-key="7271cbc8a91545ed8ccc098e85bcdc04:0">BT4.0 BLE</span></span></span></p></td></tr><tr class="tableRow-41a0302b" data-key="b208d052c4694fcd8a279a3448f2af5a"><td data-table="cell" class="tableCell-150ac604" style="text-align: left;" data-key="033aa95f28e44a4384021540e0a54c9d"><p class="blockParagraph-544a408c--noMargin-acdf7afa" data-key="8cf0cb1516ae4739b109f1dbba4d8c1c"><span class="text-4505230f--TextH400-3033861f--textContentFamily-49a318e1"><span data-key="c711e416336c489c86ceee9f03a202b6"><span data-offset-key="c711e416336c489c86ceee9f03a202b6:0">On board Storage</span></span></span></p></td><td data-table="cell" class="tableCell-150ac604" style="text-align: left;" data-key="1f477bfb72b1474492ebe1b177d0abde"><p class="blockParagraph-544a408c--noMargin-acdf7afa" data-key="75291caabe0a4e9e8b74406ea5bf691d"><span class="text-4505230f--TextH400-3033861f--textContentFamily-49a318e1"><span data-key="fe2e122a1ec24915ba990fd644f69744"><span data-offset-key="fe2e122a1ec24915ba990fd644f69744:0">MicroSD (TF) card, eMMC 8G on board (option：16/32/64G)</span></span></span></p></td></tr><tr class="tableRow-41a0302b" data-key="ed341a539929429aa90a7325a0b68a6a"><td data-table="cell" class="tableCell-150ac604" style="text-align: left;" data-key="daab4716400c4b7787b7bfa06060217e"><p class="blockParagraph-544a408c--noMargin-acdf7afa" data-key="117162c968824d1f8729de769d38e8f8"><span class="text-4505230f--TextH400-3033861f--textContentFamily-49a318e1"><span data-key="52308639456e449ebc436386fa95d336"><span data-offset-key="52308639456e449ebc436386fa95d336:0">Display</span></span></span></p></td><td data-table="cell" class="tableCell-150ac604" style="text-align: left;" data-key="3ce3f2dbb946472192aab55258e2d0d2"><p class="blockParagraph-544a408c--noMargin-acdf7afa" data-key="1a18abaeed304e2ea7e012f66794b71f"><span class="text-4505230f--TextH400-3033861f--textContentFamily-49a318e1"><span data-key="d988305bde1345c8a06d080716aa116c"><span data-offset-key="d988305bde1345c8a06d080716aa116c:0">MIPI Display Serial Interface (DSI) interface(4 data lanes)</span></span></span></p></td></tr><tr class="tableRow-41a0302b" data-key="4de1404e037c413a9526f17a929cb6f1"><td data-table="cell" class="tableCell-150ac604" style="text-align: left;" data-key="2079b8f7fb96494f8722095e21addf77"><p class="blockParagraph-544a408c--noMargin-acdf7afa" data-key="f0a2cbda20ed45bc9710456feb4b089b"><span class="text-4505230f--TextH400-3033861f--textContentFamily-49a318e1"><span data-key="4bdcf42a64404adb9f0ff44ffc4ea72b"><span data-offset-key="4bdcf42a64404adb9f0ff44ffc4ea72b:0">Camera</span></span></span></p></td><td data-table="cell" class="tableCell-150ac604" style="text-align: left;" data-key="c77c2ab554064a7c85e166ecc8272694"><p class="blockParagraph-544a408c--noMargin-acdf7afa" data-key="01fc43a43a254be9aefa8a06579cae32"><span class="text-4505230f--TextH400-3033861f--textContentFamily-49a318e1"><span data-key="f3a23206e20944aca99a50b1520ea486"><span data-offset-key="f3a23206e20944aca99a50b1520ea486:0">A CSI input connector Camera:Supports 8-bit YUV422 CMOS sensor interface,Supports CCIR656 protocol for NTSC and PAL,Supports 5M pixel camera sensor ,Supports video capture solution up to 1080p@30fps</span></span></span></p></td></tr><tr class="tableRow-41a0302b" data-key="c1472da42fdb460a9af8125c12282a8c"><td data-table="cell" class="tableCell-150ac604" style="text-align: left;" data-key="186515f3db494e0389017706524dcfee"><p class="blockParagraph-544a408c--noMargin-acdf7afa" data-key="576b8d61bfe24ec8aaf1bebfaf316cde"><span class="text-4505230f--TextH400-3033861f--textContentFamily-49a318e1"><span data-key="3523679465b8492aa896c3bf8575536b"><span data-offset-key="3523679465b8492aa896c3bf8575536b:0">Video decoder</span></span></span></p></td><td data-table="cell" class="tableCell-150ac604" style="text-align: left;" data-key="7af9983bd37244b7979566b8fbda9ca4"><p class="blockParagraph-544a408c--noMargin-acdf7afa" data-key="3b37f9f17e9d474ea1b139f435426c62"><span class="text-4505230f--TextH400-3033861f--textContentFamily-49a318e1"><span data-key="4237ff01ada54009a36df7c01bded76a"><span data-offset-key="4237ff01ada54009a36df7c01bded76a:0">Multi-format FHD video decoding, including Mpeg1/2, Mpeg4, H.263, H.264, etc H.264 high profile 1080p@60fps</span></span></span></p></td></tr><tr class="tableRow-41a0302b" data-key="4301ed7d7dd34cceab76d0069d24393f"><td data-table="cell" class="tableCell-150ac604" style="text-align: left;" data-key="a2c208924e934e6883b5dbb226d57bba"><p class="blockParagraph-544a408c--noMargin-acdf7afa" data-key="3dab758afd83413195954e1711032cc8"><span class="text-4505230f--TextH400-3033861f--textContentFamily-49a318e1"><span data-key="a665453f5e064a8da61376b7b61e4963"><span data-offset-key="a665453f5e064a8da61376b7b61e4963:0">Video encoder</span></span></span></p></td><td data-table="cell" class="tableCell-150ac604" style="text-align: left;" data-key="02b08b1f11634a3eaad4dc0b2b37dd29"><p class="blockParagraph-544a408c--noMargin-acdf7afa" data-key="025a00ac130c4c8ea72f392f64c27fbc"><span class="text-4505230f--TextH400-3033861f--textContentFamily-49a318e1"><span data-key="2f5c8b080a604b1c9f365547a55b6529"><span data-offset-key="2f5c8b080a604b1c9f365547a55b6529:0">H.264 encoder: high profile 1080p@60fps</span></span></span></p></td></tr><tr class="tableRow-41a0302b" data-key="7be0c6bd8a354384b52853fa866f4c14"><td data-table="cell" class="tableCell-150ac604" style="text-align: left;" data-key="c9a3257d76d74ce69a659ef7d95e465b"><p class="blockParagraph-544a408c--noMargin-acdf7afa" data-key="8fe88e1237bf48b98eff9d2746abbc32"><span class="text-4505230f--TextH400-3033861f--textContentFamily-49a318e1"><span data-key="0497aa591f8f47af96ea5a34bd5357e7"><span data-offset-key="0497aa591f8f47af96ea5a34bd5357e7:0">Audio input</span></span></span></p></td><td data-table="cell" class="tableCell-150ac604" style="text-align: left;" data-key="c33705fe568a4adf89836d18e9c95355"><p class="blockParagraph-544a408c--noMargin-acdf7afa" data-key="408e0d519393476bb44e9d846671afbf"><span class="text-4505230f--TextH400-3033861f--textContentFamily-49a318e1"><span data-key="5362b5d38b0c456f908e8ec717977a5f"><span data-offset-key="5362b5d38b0c456f908e8ec717977a5f:0">On board microphone</span></span></span></p></td></tr><tr class="tableRow-41a0302b" data-key="00d57960b49a4c28819b8e92a47cf388"><td data-table="cell" class="tableCell-150ac604" style="text-align: left;" data-key="ed9263f14fb44c469ac575b50c9bafba"><p class="blockParagraph-544a408c--noMargin-acdf7afa" data-key="f4a8b899c1154c6ea0669d582bbac58d"><span class="text-4505230f--TextH400-3033861f--textContentFamily-49a318e1"><span data-key="b704e355bae54e2d886cb73e5226d54c"><span data-offset-key="b704e355bae54e2d886cb73e5226d54c:0">USB</span></span></span></p></td><td data-table="cell" class="tableCell-150ac604" style="text-align: left;" data-key="48b332ab8b1a4e31aae522e6692506af"><p class="blockParagraph-544a408c--noMargin-acdf7afa" data-key="e04a5cf0427a4b219f77b51623ef3338"><span class="text-4505230f--TextH400-3033861f--textContentFamily-49a318e1"><span data-key="2d742185bff54679928563fd80d5bca8"><span data-offset-key="2d742185bff54679928563fd80d5bca8:0">1x USB 2.0 host,  1x USB 2.0 OTG</span></span></span></p></td></tr><tr class="tableRow-41a0302b" data-key="6cfcd83533404c908fa876bc2ccf8af4"><td data-table="cell" class="tableCell-150ac604" style="text-align: left;" data-key="f8ed9253453b4b2e8d1f73b93d916b56"><p class="blockParagraph-544a408c--noMargin-acdf7afa" data-key="43057a8e598845e2a8c10589f7dd4a2a"><span class="text-4505230f--TextH400-3033861f--textContentFamily-49a318e1"><span data-key="5ee73a1a29874879ab8e245dafddfde8"><span data-offset-key="5ee73a1a29874879ab8e245dafddfde8:0">Buttons</span></span></span></p></td><td data-table="cell" class="tableCell-150ac604" style="text-align: left;" data-key="58cd36111ca8420c9c7756c8a6904930"><p class="blockParagraph-544a408c--noMargin-acdf7afa" data-key="935991fbeb6243678c36b0a621bcd859"><span class="text-4505230f--TextH400-3033861f--textContentFamily-49a318e1"><span data-key="a2423ef688d145a29661748ae85d3403"><span data-offset-key="a2423ef688d145a29661748ae85d3403:0">Reset button, Power button</span></span></span></p></td></tr><tr class="tableRow-41a0302b" data-key="e100905b433d4b70b82ebf03f4c253de"><td data-table="cell" class="tableCell-150ac604" style="text-align: left;" data-key="9dfc64586c724e1c895477bb014d6888"><p class="blockParagraph-544a408c--noMargin-acdf7afa" data-key="83c135186c2c4d699706cb5125ba74f4"><span class="text-4505230f--TextH400-3033861f--textContentFamily-49a318e1"><span data-key="0d62dd7d663a46c189d0b7bb22a4d760"><span data-offset-key="0d62dd7d663a46c189d0b7bb22a4d760:0">Leds</span></span></span></p></td><td data-table="cell" class="tableCell-150ac604" style="text-align: left;" data-key="173771c5d0424d9484bceedaf78ee769"><p class="blockParagraph-544a408c--noMargin-acdf7afa" data-key="f26fe3ad4247435eaf09baab31e5f4e5"><span class="text-4505230f--TextH400-3033861f--textContentFamily-49a318e1"><span data-key="612ac6e9a45642b5a3f47fe091fbf56a"><span data-offset-key="612ac6e9a45642b5a3f47fe091fbf56a:0">Red, Green, Blue</span></span></span></p></td></tr><tr class="tableRow-41a0302b" data-key="6bc2f5503faf4c6e864cc66fdfb9b829"><td data-table="cell" class="tableCell-150ac604" style="text-align: left;" data-key="9e2abf15d81648a5a49e2ebee8230e53"><p class="blockParagraph-544a408c--noMargin-acdf7afa" data-key="1d0941dc89ca4e25af3069166ee43eec"><span class="text-4505230f--TextH400-3033861f--textContentFamily-49a318e1"><span data-key="c6eb385026544362b3da7d0c63a7cc1b"><span data-offset-key="c6eb385026544362b3da7d0c63a7cc1b:0">battery</span></span></span></p></td><td data-table="cell" class="tableCell-150ac604" style="text-align: left;" data-key="057f86ad5ef049419794694551ee5b3f"><p class="blockParagraph-544a408c--noMargin-acdf7afa" data-key="6aea0cbed6b94339bdbc29319c8ae1ce"><span class="text-4505230f--TextH400-3033861f--textContentFamily-49a318e1"><span data-key="4eeee955426a45109c0fdf3825d7ab5e"><span data-offset-key="4eeee955426a45109c0fdf3825d7ab5e:0">3.7V lithium battery power support</span></span></span></p></td></tr><tr class="tableRow-41a0302b" data-key="524cbc7f51ed44548c885523ec5bc5e8"><td data-table="cell" class="tableCell-150ac604" style="text-align: left;" data-key="3641db08f5ce4bf4b771d7733366320f"><p class="blockParagraph-544a408c--noMargin-acdf7afa" data-key="5b6865a260614afb81c6f6a2530e66ed"><span class="text-4505230f--TextH400-3033861f--textContentFamily-49a318e1"><span data-key="cfccd38c49684d158caeb58ab54dce4c"><span data-offset-key="cfccd38c49684d158caeb58ab54dce4c:0">Sizes</span></span></span></p></td><td data-table="cell" class="tableCell-150ac604" style="text-align: left;" data-key="756e181e27fa473885996d5ca5d1a1ef"><p class="blockParagraph-544a408c--noMargin-acdf7afa" data-key="2603739bebd143a1954e35fb8c28e8e5"><span class="text-4505230f--TextH400-3033861f--textContentFamily-49a318e1"><span data-key="ce59cf1c9d4945c0b6985174f62a2d2c"><span data-offset-key="ce59cf1c9d4945c0b6985174f62a2d2c:0">51 mm × 51mm</span></span></span></p></td></tr><tr class="tableRow-41a0302b" data-key="12417a3d43b14709838d3fde1acb9a07"><td data-table="cell" class="tableCell-150ac604" style="text-align: left;" data-key="1765df3d19bb44f8aac3411c8eb0c01a"><p class="blockParagraph-544a408c--noMargin-acdf7afa" data-key="04d7aaf2f5374305addabb66e6bd2e89"><span class="text-4505230f--TextH400-3033861f--textContentFamily-49a318e1"><span data-key="b209225ae4934c81b0a007ce54da2a28"><span data-offset-key="b209225ae4934c81b0a007ce54da2a28:0">Weight</span></span></span></p></td><td data-table="cell" class="tableCell-150ac604" style="text-align: left;" data-key="93d950fb8a86452482d3d00d601e2a30"><p class="blockParagraph-544a408c--noMargin-acdf7afa" data-key="1af859d024844175a6433796c4976097"><span class="text-4505230f--TextH400-3033861f--textContentFamily-49a318e1"><span data-key="6156c7d5809c4d3d9348bc15c2fdcfa5"><span data-offset-key="6156c7d5809c4d3d9348bc15c2fdcfa5:0">40g</span></span></span></p></td></tr></tbody></table></div></div></div></div></div></div>

______________________________________________________
[![Solid90](https://raspberry-valley.azurewebsites.net/img/raspibanner.jpg)](https://github.com/D3vD3m0n/)| 
