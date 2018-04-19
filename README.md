All PoCs are about Android Bluetooth(Bluedroid).


avrcp_CVE-2017-13281.c is the poc of CVE-2017-13281.

$ mv avrcp_CVE-2017-13281.c blue-5.37/profiles/audio/avrcp.c

just replace blue-5.37/profiles/audio/avrcp.c with poc, and compile the source code on ubuntu 16.04， run bluetoothd manually, and paired my pixel xl with my laptop. Once paired, the attack payload will be sent automatically.







Note: just for research and test, not for illegal use.