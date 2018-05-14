# Malduino Scripts
The malduino scripts I use. Contains both malicious and non-malicious scripts, all designed for the Malduino Elite. Also contains my current modified version of the Malduino Elite firmware, which has various upgrades. It can detect when the system has enumerated the device and then run the script, and it uses an upgraded [HID library](https://github.com/NicoHood/HID) so it can use media keys and system keys. It also includes a few useful extra commands. 
My system for script naming is that non-malicious scripts start with a 0 (ie. 0000 - 0111) and malicious (actual hacking) scripts start with a 1 (ie. 1000 - 1111).
# List of scripts by DIP settings:
Non-Malicious (pranks):  
0000: Set desktop background to hotdog - Windows   
0001: Hidden icons prank - Windows 7  
0010: Hidden icons prank - Windows 10  
0011: Upside down desktop - Windows  
0100: Windows 93 prank - Windows  
0101: Install NCage on Chrome - Windows  
0110: Rickroll at 4:20pm - Windows  
  
Malicious:  
1111: Meterpreter through powershell - Windows (requires metasploit)  
1110: Meterpreter through wget - Windows (requires pastebin and metasploit)  
1101: Wifi Password Grabber through FTP - Windows (requires FTP server)
1100: Mimikatz download and export - Windows (requires webserver with PHP)  
