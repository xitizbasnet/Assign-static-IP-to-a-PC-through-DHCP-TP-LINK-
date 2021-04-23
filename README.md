# Assign-static-IP-to-a-PC-through-DHCP-TP-LINK-
Assign static IP to a PC through DHCP: TP-LINK 

-----------------------------
Step: 1

1. Press: "Win + R"
2. Type: "CMD" and hit "ENTER"
3. Type: "ncpa.cpl"
4. Type: "ipconfig /all"
5. Lok to the physical address: "D0-50-99-2D-3E-EB"
6. Paste this "D0-50-99-2D-3E-EB" in notepad
7. Replace "D0-50-99-2D-3E-EB" with "D0:50:99:2D:3E:EB" in notepad
8. END

--------------
Step: 2

1. First login to the Router: 192.168.1.1
2.  GO to the Interface Setup
3.  Go to the "LAN"
4.  Go to the DHCP Table
5.   Assign a IP address. Eg: 192.168.1.150
6.   Assign Mac address "D0:50:99:2D:3E:EB"
7.   "Save" the configuration
8.   END

-------------
