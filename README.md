# Overview
Use at your own risk!

IF you're here, you likely are getting a BSOD with crowdstrike.  There is a short period of time where the device comes onle before it bluescreens.  If you can rename the driver in this window it will clear up the issue by renaming(c-00000291*.sys)

Test this on a few devices frist.

# Access

You must have access remotely to the devices to execute this script and have access to rename the crowdstrike driver

# How to use

Create a working folder: c:\scripts (or clone this repo locally)

Add a file called devices.txt that contains a list of all the devices you are attempting to remediate

Execute "cleanup.bat"  This will spawn new command window and attempt to rename the driver once the device is reachable.  Note, it will do this indefinately. To stop execution you must kill all the command windows.  You can do this manually or use something like taskkill /f /im cmd.exe


