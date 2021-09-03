# Getting into network with 802.1x with cert protection
Not a great hack, still may be usefull in some situations.  

What we have:  
1) WiFi protected with 802.1x + certificate auth;
2) iPad authorized to this network.

What we need:
1) access protected network with our blessed kali.

Google usually says, that an iPad without cellular and SIM can't be used as a proxy. However, there is a way to make it work in that way. How to:
1) Set up AirDrop connection between an iPad and a Macbook;
2) Install "Proxiy" application (or analogue) from AppStore on both devices;
3) Configure a listener on the Macbook and proxy in the iPad;
4) Config proxychains accordint to "Proxiy" config;
5) ???
6) U're hackerman

You may meet an error with your proxychains on the mac. Default macbook settings disallow applications from default path to be proxified. 
So, you need to reinstall an nmap/curl/etc to the another location. 
