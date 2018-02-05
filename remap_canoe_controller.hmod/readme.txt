=== Remap Canoe Controller ===

This hmod allows you to edit the controller inputs in Canoe.
                  
The A and B buttons are modified already, A acts as B and B acts as A.
 
Installs to:                                          
/etc/preinit.d                                        
and                                                   
/etc/sdl2-override                                   

Any controller connected to the ports at the front will be recognized as Nintendo Clovercon.

You can edit gamecontrollerdb.txt BEFORE you install the hmod, if you wish.

Updated current database with additional 60 controllers for future purpose.

How do I edit the inputs?

USB-host:
1. Go to usb:/hakchi/canoecontrollerconfig
2. Edit gamecontrollerdb.txt

Others:
1. FTP to /etc/sdl2-override
2. Edit gamecontrollerdb.txt

Nintendo Clovercon example:
If you want to swap X and Y, simply change
y:b3,x:b2
to
y:b2,x:b3

Thanks to:
madmonkey
DanTheMan827
swingflip
