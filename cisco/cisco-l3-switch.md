Cisco Catalyst 3550
=====================

L3スイッチ。  
半年前に中古で買ってからまったく起動してなかった。  
勉強しよう。

- 型番: WS-C3550-48-EMI
- 10/100Base-TX x 48ポート 1000Base GBIC x 2ポート

超久しぶりに起動した時のシリアルコンソールに流れたログ
----------------------------------------------------

```
POST: Ethernet Controller Tests : End, Status Passed
POST: Loopback Tests : BeginBase ethernet MAC Address: 00:0a:41:15:13:00
Xmodem file system is available.
The password-recovery mechanism is enabled.
Initializing Flash...
flashfs[0]: 14 files, 3 directories
flashfs[0]: 0 orphaned files, 0 orphaned directories
flashfs[0]: Total bytes: 15998976
flashfs[0]: Bytes used: 5105152
flashfs[0]: Bytes available: 10893824
flashfs[0]: flashfs fsck took 18 seconds.
...done Initializing Flash.
Boot Sector Filesystem (bs:) installed, fsid: 3
Loading "flash:c3550-i5q3l2-mz.121-8.EA1c/c3550-i5q3l2-mz.121-8.EA1c.bin"...#######################################################################################################################################################################################################################################################################################################################################################################################################

File "flash:c3550-i5q3l2-mz.121-8.EA1c/c3550-i5q3l2-mz.121-8.EA1c.bin" uncompressed and installed, entry point: 0x3000
executing...

              Restricted Rights Legend

Use, duplication, or disclosure by the Government is
subject to restrictions as set forth in subparagraph
(c) of the Commercial Computer Software - Restricted
Rights clause at FAR sec. 52.227-19 and subparagraph
(c) (1) (ii) of the Rights in Technical Data and Computer
Software clause at DFARS sec. 252.227-7013.

           cisco Systems, Inc.
           170 West Tasman Drive
           San Jose, California 95134-1706



Cisco Internetwork Operating System Software
IOS (tm) C3550 Software (C3550-I5Q3L2-M), Version 12.1(8)EA1c, RELEASE SOFTWARE (fc1)
Copyright (c) 1986-2002 by cisco Systems, Inc.
Compiled Fri 15-Feb-02 10:50 by antonino
Image text-base: 0x00003000, data-base: 0x006675E0


Initializing flashfs...
flashfs[1]: 14 files, 3 directories
flashfs[1]: 0 orphaned files, 0 orphaned directories
flashfs[1]: Total bytes: 15998976
flashfs[1]: Bytes used: 5105152
flashfs[1]: Bytes available: 10893824
flashfs[1]: flashfs fsck took 8 seconds.
flashfs[1]: Initialization complete.
...done Initializing flashfs.
POST: CPU Buffer Tests : Begin
POST: CPU Buffer Tests : End, Status Passed
POST: CPU Interface Tests : Begin
POST: CPU Interface Tests : End, Status Passed
POST: Switch Core Tests : Begin
POST: Switch Core Tests : End, Status Passed
POST: CAM Subsystem Tests : Begin
POST: CAM Subsystem Tests : End, Status Passed
POST: Ethernet Controller Tests : Begin
POST: Ethernet Controller Tests : End, Status Passed
POST: Loopback Tests : Begin
POST: Loopback Tests : End, Status Passed

cisco WS-C3550-48 (PowerPC) processor (revision D0) with 65526K/8192K bytes of memory.
Processor board ID CAT0625X0T3
Last reset from warm-reset
Bridging software.
Running Layer2/3 Switching Image

Ethernet-controller 1 has 12 Fast Ethernet/IEEE 802.3 interfaces

Ethernet-controller 2 has 12 Fast Ethernet/IEEE 802.3 interfaces

Ethernet-controller 3 has 12 Fast Ethernet/IEEE 802.3 interfaces

Ethernet-controller 4 has 12 Fast Ethernet/IEEE 802.3 interfaces

Ethernet-controller 5 has 1 Gigabit Ethernet/IEEE 802.3 interface

Ethernet-controller 6 has 1 Gigabit Ethernet/IEEE 802.3 interface

48 FastEthernet/IEEE 802.3 interface(s)
2 Gigabit Ethernet/IEEE 802.3 interface(s)

The password-recovery mechanism is enabled.
32K bytes of flash-simulated non-volatile configuration memory.
Base ethernet MAC Address: 00:0A:41:15:13:00
Motherboard assembly number: 73-5701-06
Power supply part number: 34-0967-01
Motherboard serial number: CAT06240AE8
Power supply serial number: DAB06170JW3
Model revision number: D0
Motherboard revision number: C0
Model number: WS-C3550-48-EMI
System serial number: CAT0625X0T3

         --- System Configuration Dialog ---

Would you like to enter the initial configuration dialog? [yes/no]:
00:00:41: %SPANTREE-5-EXTENDED_SYSID: Extended SysId enabled for type vlan
00:00:46: %SYS-5-RESTART: System restarted --
Cisco Internetwork Operating System Software
IOS (tm) C3550 Software (C3550-I5Q3L2-M), Version 12.1(8)EA1c, RELEASE SOFTWARE (fc1)
Copyright (c) 1986-2002 by cisco Systems, Inc.
Compiled Fri 15-Feb-02 10:50 by antonino
00:00:51: %LINK-3-UPDOWN: Interface FastEthernet0/1, changed state to up
00:00:52: %LINEPROTO-5-UPDOWN: Line protocol on Interface FastEthernet0/1, changed state to up
00:01:23: %LINEPROTO-5-UPDOWN: Line protocol on Interface Vlan1, changed state to up
00:01:23: AUTOINSTALL: Vlan1 is assigned 192.168.0.3
%Error opening tftp://255.255.255.255/network-confg (Timed out)
%Error opening tftp://255.255.255.255/cisconet.cfg (Timed out)
%Error opening tftp://255.255.255.255/router-confg (Timed out)
%Error opening tftp://255.255.255.255/ciscortr.cfg (Timed out)
% Please answer 'yes' or 'no'.
Would you like to enter the initial configuration dialog? [yes/no]: 
```
