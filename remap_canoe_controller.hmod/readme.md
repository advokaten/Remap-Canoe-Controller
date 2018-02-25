-----------------------
Name: Remap Canoe Controller
Creator: Advokaten
Category: Controller
-----------------------
This hmod allows you to edit the controller inputs in Canoe.
                  
+ The A and B buttons are already swapped.

- Any controller connected to the port(s) at the front of the Mini, will be recognized as Nintendo Clovercon.

+ You can edit gamecontrollerdb.txt before and after you install the hmod.

- Updated current database with an additional 60 controller mappings for future purpose.

<br>

How do I edit the inputs?

USB-host:
```
1. Go to usb:/hakchi/canoecontrollerconfig
2. Edit gamecontrollerdb.txt
```

Others:
```
1. FTP to /etc/sdl2-override
2. Edit gamecontrollerdb.txt
```

<br>
Edit Nintendo Clovercon example:

If you want to swap X and Y, simply change

```
y:b3,x:b2
```
to
```
y:b2,x:b3
```

<br>

Installs to:                                          

```
/etc/preinit.d                                        
```
and       
```                                            
/etc/sdl2-override                                   
```

<br>

YouTube Tutorial:

<a href="http://www.youtube.com/watch?feature=player_embedded&v=B_zTxRl7yg4
" target><img src="http://img.youtube.com/vi/B_zTxRl7yg4/0.jpg" 
alt="Remap Canoe Controller Advokaten SNES Mini" title="Click to open 'Remap Canoe Controller Tutorial' in your browser" width="360" height="240" border="10" /></a>

<br>
Thanks to:

madmonkey

DanTheMan827

swingflip
