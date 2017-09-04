# Aircrack-ng
Aircrack-ng is an 802.11 WEP and WPA-PSK keys cracking program that can recover
keys once enough data packets have been captured. It implements the standard FMS
attack along with some optimizations like KoreK attacks, as well as the
all-new PTW attack, thus making the attack much faster compared to other WEP
cracking tools.


## Modification
The program has the same functionalities of the original Aircrack-ng. The changes concern the GUI of airodump-ng.
I've added:
- Sequence Number of the packet
- RSSI


## Compiling

 * Compilation:

    `make`

 * Compilation on *BSD or Solaris:
 
    `gmake`

 * Strip debugging symbols:

    `make strip`

 * Installing:

    `make install`

 * Uninstall:

    `make uninstall`


