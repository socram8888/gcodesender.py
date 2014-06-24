gcodesender.py
==============

Basic gcode sender in Python.

This script has been tested on a pcDuino v2 sending gcode to a Printrbot.  It should also work on an Arduino Yun.

Help: ./gcodesender.py --help

Example usage:

./gcodesender.py -p /dev/ttyACM0 -f /media/UNTITLED/shoulder.g

Code snippets and basic idea taken from:
http://onehossshay.wordpress.com/2011/08/26/grbl-a-simple-python-interface/
