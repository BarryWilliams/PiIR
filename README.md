# PiIR
PiIR - pronounced "peer" - Raspberry Pi Universal Remote

Some inspiration was taken from [this project](http://mvartan.com/2014/11/25/controlling-your-tv-or-any-ir-device-with-raspberry-pi/)

follow the project on [pivotal tracker](https://www.pivotaltracker.com/n/projects/1505034) 

# Purpose
The intent of this project is to create a universal remote system that is accessable on any device with a browser. Eventually native apps might be made.

I intend to write the backend in golang exposing a REST API. A static web app will then connect to this API, display all devices and when a device is selected it will show all the commands available for that device. Underneath, the backend calls [LIRC](http://www.lirc.org/). I have further plans which have been captured in the Pivotal Tracker.

Currently, I am blocked because of hardware issues.
