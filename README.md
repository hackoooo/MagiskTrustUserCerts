# MagiskTrustUserCerts
Make Android user certs trusted by system using Magisk module.

Above Android 7.0, if you set the wifi with a proxy, then monitor the HTTP/s data using Charles, you may troubleshooted by 'unknown certificates'.  
In order to capture the data, you can use Xposed framework or Frida etc. Here we just add the user certs to system and they will be trusted by system.  

# Getting Started
1. Install Magisk
2. Zip this project as a MagiskModule
3. Load this modue using MagiskManager and then reboot

Done.
