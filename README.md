# GPS_Video_Sync
GPS and Video Synchronization Project 

This project was created while I was attending the University of Hawaii at Manoa under Professor Sasaki.

This software will synchronize videos recorded while using a gps recording device. Note that the videos must be recorded by a device with an up-to-date timestamp to properly synchronize the video playback with the GPS information. The GPS information must be recorded in the following format, with .v2 extension:

Start
31/11/32|15:35:67.50|21.34,-157.88,5.55,90.0

The first line signifies the start of a route, labeled "Start". All gps data for the route will be appended by line with successive gps recordings. 

Sample files are provided for testing purposes:
  data.v2
  GOPR2280.MP4
  
A demo video is also provided:
  DemoVideo
