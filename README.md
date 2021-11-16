# Asus ROG Strix G15 - G512LV - OpenCore EFI
 
<li>Tested on macOS <b>BigSur</b> and <b>Monterey</b>.</li>
 
<h1>Important Notes</h1>
<li>OpenCore version: <b>0.7.5</b></li>
<li>Add your <b>SMBIOS</b> details and <b>mac address</b> in config.plist. <a href="https://dortania.github.io/OpenCore-Install-Guide/config-laptop.plist/coffee-lake-plus.html#platforminfo">Use this guide</a></li>
<li>If you want to install macOS on the same drive as Windows, extend your laptop default EFI partition to over 200MB. You may break your Windows bootloader if it's 200MB(default) or less.</li>
<li>The AirportItlwm.kext is for <b>Monterey</b> only, <a href="https://github.com/OpenIntelWireless/itlwm/releases">use the Big Sur version if you are not on Monterey</a></li>
<li><a href="https://github.com/xzhih/one-key-hidpi">For Enabling macOS HiDPI</a></li>
<li>You can use this EFI for other models like G512LI/LW, G712LI/LV/LW, and probably even other Asus gaming laptops(exept AMD ones) like the Zephyrus series as there isn't much difference in internal structure. Probably you'll need to remap USB and change some values for CPU, iGPU, Audio, etc in config.plist according to <a href="https://dortania.github.io/OpenCore-Install-Guide">Dortina's official guide</a> for your device.</li>
 
<h1>Specs</h1>
<li>Intel® Core™ i7 10750H Processor, 2.6 GHz</li>
<li>NVIDIA® GeForce® RTX 2060 (DISABLED)</li>
<li>16G RAM</li>
<li>AX201 Wi-Fi 6 (802.11 ax (2x2))</li>
<li>ELAN1203 Touchpad</li>
 
<h1>What works</h1>
<li>Wifi</li>
<li>Bluetooth</li>
<li>Eathernet</li>
<li>iMessages</li>
<li>Trackpad</li>
<li>144hz display</li>
<li>Handoff</li>
<li>etc</li>
 
<h1>What does NOT work</h1>
<li>Airdrop (due to bluetooth limited support)</li>
<li>HDMI and USB-C DisplayPort output (they're <b>wired</b> to the Nvidia graphic, there's no way to use them in hackintosh)</li>
 
<h1>Credits</h1>
<li>Thanks to <a href="https://github.com/dkoluris">Dennis Koluris</a> for power managment fix.</li>
<li>Thanks to <a href="https://github.com/ClefairyBlame">ClefairyBlame</a> for trackpad fix.</li>
