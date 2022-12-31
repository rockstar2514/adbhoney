# adbhoney
Android Debug Bridge is a tool that can be used for various developer purposes on emulated devices or actual phones. But there is a flaw in adb wherein on port 5555 once adb is set up,
no further checks are performed. So, if the port 5555 is exposed adb commands can be sent through it to the adb daemon running on the device. This honeypot simulates an adb process running on open port 5555 to attrach hackers and
logs all commands made.
