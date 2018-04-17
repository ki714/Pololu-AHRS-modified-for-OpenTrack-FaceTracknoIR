# Pololu-AHRS-modified-for-OpenTrack-FaceTracknoIR
Incorporated HATire plugin code 

1. Open Arduino IDE and notice the COM-Port ID/Number
   Tools/Port:COM# (Mine at COM6)

2. Double click OpenTrack and at the Input dropdown, select Hatire Arduino. Click on the hammer and select the appropriate COM#. 
   Under Axis Configuration, set the appropriate axis per Yaw/Pithc/Roll and enable all three (not X,Y and Z)
   BautRate: 115200, Data bits 8, Parity None, Stop bits 1 and Flow control None.
   
3. Similar setup for FaceTracknoIR. 

4. If you received no tracking data in 15-20 seconds, You may need to initialize Arduino IDE and check the Serial Monitor tap for 
   data streaming, then closed both Serial Monitor and Arduino IDE. Hit Start again on either OpenTrack or FaceTracknoIR. 
   
   
