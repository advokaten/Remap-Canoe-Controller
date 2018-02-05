=== Canoe Controller Config ===

This hmod allows you to edit the controller inputs in Canoe.

Installs to:
/etc/preinit.d
and
/etc/sdl2-override

How do I edit the inputs?
USB-host:
usb:/hakchi/canoecontrollerconfig will be created

Others:
FTP to /etc/sdl2-override

All:
Edit gamecontrollerdb.txt

Nintendo Clovercon example:
If you want to swap X and Y, simply change
y:b3,x:b2
to
y:b2,x:b3

Note: If you are using 8bitdo recievers, any controller connected to it will be recognized as Nintendo Clovercon.

You can edit gamecontrollerdb.txt BEFORE you install the hmod, if you wish.

Thanks to:
madmonkey
DanTheMan827