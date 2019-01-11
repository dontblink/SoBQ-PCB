# SoBQ-PCB
SPHINX OF BLACK QUARTZ, JUDGE MY VOW

## Purpose
Friend bought me a few switches, wanted to build a keyboard worthy of them :)
Alot of this project is predicated on me wanting to learn a bunch of stuff. Will be attempting to use a bunch of different tools for the first time 
- CMake
- unit test suites (maybe throwtheswitch) + jenkins/travis
- some tools from the llvm suite - clang, static analyzers, etc.
Will also be using a few peripherals for the first time - haven't really messed with SPI before, nor DMA, nor have I really ever understood USB protocols. 
In addition, wanted to make a layout that suites me the best, and kinda started making a list of things i wanted - encoder control, maybe integration with that aurora rgb project if I can figure out 
 
## Layout:
Took some cues from the typical 75% layout, but shifted over the column row so that compatability with standard keysets is ~mostly good~ eh, could be worse. 
There still might be issues with the right hand bottom row layout, used 1u there :(
Future updates I might use 3x 1.25 bottom row keys, have a slight gap next to the arrow cluster
External of layout - I have a novel idea for encoder placement based on some of the fancier logitech keebs, but not really sure if it's ergonomic enough to be useful. we'll see. 
![Layout](Images/Layout.png?raw=true "SOBQ")

## Features:
Kailh sockets, Cortex M4 mcu, full rgb, oled

## Firmware:
LOL C YA IN 2020
