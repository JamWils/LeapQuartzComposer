LeapQuartzComposer
==================
Author: Chris Birch
Date: 05/01/13

Quartz Composer Plugin to enable QC compositions to receive data from Leap Motion device using Leap SDK 0.7.4.

Background:

Plugin inspired by the pre SDK 0.7 "LeapQC" project on GitHub (see credits). 

Credits:

Jon Hammond for getting me involved with this cool device.
https://www.facebook.com/justaddmusic
 
Andrew Pouliot
http://darknoon.com/about/
https://github.com/darknoon/LeapQC



Changes:

v0.2 - Wed 27 Feb 13

Updated to use Leap SDK 0.7.4

Added gesture Support!

fixed crash by removing non arc code and upgrading to latest library

Added some macros to simplify dictionary primitive type boxing.

cleaned up code




v0.11 - Sat 19 Jan 13

- Added QC "pretty" names for ports
- Exposed Frame dictionary
- Exposed Screens array
- Exposed Hands array
- Exposed Fingers array
- Exposed Pointables array
- Exposed Tools array
- User can now choose which properties are exposed by setting an input Bool with corresponding name.
- User can now choose which arrays (tools,fingers,pointables) are exposed inside hand structures.