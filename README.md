TCP/IP server implemented using National Instruments' LabVIEW
=============================================================

Interface
---------

This simple TCP/IP server runs on the port 9999 and accepts only 2 commands:

 * p - print back current date/time
 * q - quit connection

Sample session
--------------

    $ socat TCP4:localhost:9999 -
    p
    27.11.12
    12:41
    p
    27.11.12
    12:42
    q
    $

Block diagram
-------------

![LabVIEW screenshot](http://i.imgur.com/iNUTJ.png)
