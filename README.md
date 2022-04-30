# Benchies
This repository contains 3d Benchy prints and their associated klipper configurations and slicer profiles. Major changes to
the slicer settings or klipper configuration will be denoted by a release including the binaries for both. 
Both printers are running Klipper firmware attached to a Raspberry pi. I use Fluidd for an interface

# The printers

## Ender 3 V2 (old trusty)
Gifted to me by my best friend Aaron Cleveland ([@notyourswiftdev](https://github.com/notyourswiftdev)). He gave it to me with a BL Touch

### Upgrades:
- Bed: Borosilicate glass bed
- Hotend/Extruder: Microswiss direct drive
- Z Axis: dual, no timing belt

### Known issues:
- Tramming/leveling is difficult due to the X-axis being misaligned. 
  - A timing belt across the dual z-axis may help, but I fear one or both of the rods may be bent.

## Ender 3 S1
I bought this as a gift to myself after being hired on at [Nautilus](https://github.com/nlsinc)

### Upgrades:
Hotend: S1 pro (awaiting delivery)

### Known issues
- There's an issue with the extruder/hotend being misaligned/skewed which sometimes causes it to crash into the bed because the right side comes into contact 
prior to the sensor coming into contact with the bed.
  - The crashing doesn't cease unless the machine is powered off (the nozzle continues trying to lower). 
  - This issue caused me to fiddle with the extruder a little too much and I've turned the adjustment screw past the point of no return. RIP extruder
