# Fish Finders / Fish Sonar

Being in a boat is only an advantage if you don't scare off all the fish, or if
you know where to put your boat (where all the fish are). For that reason, I
picked up a "transom-mount fish sonar" for ~$120, the [Garmin Striker 4 Fish
Sonar](https://www.amazon.com/Garmin-010-01550-00-Striker-4/dp/B017NI17HQ).

## Fish Sonar Basics

A few things to note:

1. Fish sonars use a good amount of power, since they send out sound clicks and
   listen for how long it takes for the sound to travel back to the device in
   order to gauge depth and whether there are fish. This means they almost
   always require an external lead acid battery. The Garmin Striker 4 that I
   purchased draws about 0.5 amps, so a small 12v battery rated at 6ah would be
   enough to last me approximately a half day. This battery can be a small thing
   like this:

   <img alt="A small lead-acid battery" src="./img/lead_acid_battery.jpg" height="150">

   ...and wiring it is really easy. Red cable to read lead. Black cable to black
   lead. Nothing complicated, it turns on and works!

   In practice if you're using a trolling motor, you can just hook your fish
   sonar up to your large deep cycle marine battery.

2. The thing that sends out sounds and receives them back is called a
   [transducer](). The transducer that came out of the box with my Garmin
   Striker 4 was a _dual beam transducer_, meaning it can send out two
   frequencies at the same time.

   <img alt="Transducer Frequencies" src="./img/200khz_vs_50khz.png" width="400">
   
   The beam of a transducer set to 200 kHz, left, covers less area but shows
   much more detail. This is the frequency that's most useful for shallow-water
   applications. The 50 kHz transducer beam, right, sacrifices some detail for a
   broader beam, useful for searching deep water.


If you're trying to find fish from the land, a fish sonar like the one I bought
is probably not good. You'd need to either find a castable transducer (which I
have not seen on the market for my sonar) OR buy something [like
this](https://www.amazon.com/iBobber-Wireless-Bluetooth-Android-devices/dp/B00LEA2FS0)
which seems to have terrible reviews. I don't know if you can just manually hold
your transducer in the water and see if there are fish; I suspect it doesn't
work too well because transducers are directional.

## Kinds of Fish Sonar

### Traditional

Traditional / cheap sonars only show arches under your boat so you don't actually know what kind of shape they have, you can only assume / hope they are actually fish.

<img alt="Fish finder arches" src="./img/fish_finder_arches.png" width="400">

### Downscanning

Downscanning sonar (e.g Garmin DownVu) does a higher resolution / top-down scan that reveals the actual topography of the floor. This can reveal hidden fishies such as halibut / flounders! This is however a little more expensive.
