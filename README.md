# SpotyFloppy
A simple project to connect your Raspberry and a Floppy Disk attached (USB) with a Spotify subscription, reviewing on Internet, appears several projects like this, https://www.dinofizzotti.com/blog/2020-02-05-diskplayer-using-3.5-floppy-disks-to-play-albums-on-spotify/, an excellent starting point to understand and to discover the options.
Finally I decided to create my own project with a physical interaction and reusing the GPIOs of the Raspberry.

The idea was to reuse my old collection (hundreds) of Disks 2HD 1.44 Mb and useless as of today

The way to work and the functionality is very simple, 
  1.- To store, specific information in a disquette (Artist, Album and a couple of things more
  2.- Push a button to start the process
  3.- Wait a couple of seconds and.....
  4.- The Album of this Artist plays and the music appears :) (YEAH!!!!!!!!!)
  5.- Change the disquette and repeat the process :) :).
    
The BOM:
    
    * 1 Raspberry Pi 3 B (Tested and working)
    * 3 leds (Red, Yellow and Green)
    * 3 resistors:
	* Red led --> 301
	* Yellow led --> 221
	* Green led --> 47R0

* 6 Dupont cables
* 1 Push Button
	* 1 External Diskette Drive (USB Connected)
	* 1 BT transmitter and Jack cable (male To male)
	* A lot of illusion to learn ;)

The steps to configure this, are very simple and tested on Raspberry PI 3B
