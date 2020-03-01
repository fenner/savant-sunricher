# Savant profile for Sunricher WiFi lighting controller

The Sunricher "[WiFi-RF Converter](https://www.sunricher.com/wifi-rf-convertor-sr-2818win.html)" provides an IP interface to
their RF-controlled LED drivers.  This line is OEM'd by American Lighting
under the name "TruLux".

You need to use the app to link the WiFi lighting controller with the
drivers.  The app gives you 8 slots to link drivers; these correspond
to 8 bits worth of addressing information.  This gives you the ability
to control multiple drivers at once if you want.

In Savant, use address 1 for driver 1; address 2 for driver 2; address 3 for driver 1+2;
address 4 for driver 3, etc.  You likely want to use 1,2,4,8,16,32,64,128
for the 8 individual drivers or 255 for all.

