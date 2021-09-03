# Getting into network with 802.1x with cert protection
Not a great hack, still may be usefull in some cases.  

What we have:  
1) A WiFi protected with 802.1x & certificate auth;
2) An iPad authorized in this network.

What we need:
1) To obtain an access to the protected network with our blessed kali.

Google usually says, that an iPad without a cellular connection and a SIM can't be used as a proxy. However, there is a way to make it work that way. How to:
1) Set up an AirDrop connection between an iPad and a Macbook;
2) Install Proxiy app (or analogue) from AppStore on both devices;
3) Configure a listener on the Macbook and a proxy in the iPad;
4) Config proxychains according to the "Proxiy" config;
5) ???
6) U're hackerman

You may meet an error using proxychains on the mac. Default macbook settings disallow applications from default path to be proxified. 
So, you will need to reinstall nmap/curl/etc to another location. 
