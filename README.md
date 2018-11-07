# ink2snmp
Read ink levels and convert it to SNMP.

  * Install libinklevel and ink by Markus Heinz.
  * Ink command supports usb, parallel and network printers.
  * http://ink.sourceforge.net/
  * Test and setup the 'ink' command for your printer.
  * Add your working ink command to the top of the ink2snmp script.
  * Add the following to your /etc/snmp/snmpd.conf

```pass .1.3.6.1.2.1.43 /bin/bash /usr/local/bin/ink2snmp```
