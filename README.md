# Makernet

The fast, intuitive way to make awesome portable projects where you don’t have to reinvent the wheel

## The Idea

MakerNet is modular toolbox for rapidly constructing small, portable objects in a consistent way. We aim to democratize the construction of actual electronic devices you can hold, play with, put on your desk and share with people. 

Too many young makers today get stuck at the breadboarding stage. Sadly, going from breadboard to something more needs a vast amount of new skills. This deprives so many creative people the satisfaction of building something finished. 

How do we make it easier to get the payoff a project you can take for show and tell? How do we fill every aspiring maker's shelves with finished concepts that inspire them and others? 

MakerNet is a framework of PCB designs, Arduino libraries, laser cut plans and mounting hardware. Everything works together without soldering to let you build awesome projects that inspire! 


## What does it do?

MakerNet is in the concept stage, although there have been some light exploratory prototypes. Some of the intended features:

Pre-made modules: A small library of cool modules such as a rotary encoder, 8x8 matrix, capacitive slider, MCU board, neopixel driver, LCD/OLED screen, 4-way control pad, sensors, etc. All of them will be compatible and interoperable

Bus Architecture: MakerNet will be built on a bus architecture (initially I2C, later RS485) that allows true "plug and play" for most projects

No Soldering: Everything is connected with JST-SH 6 pins and can be daisy chained

Case plans: Every component has a clear mounting strategy, eliminating guesswork on how to put it into a case. Mix and match modules to create the control panels of your dreams! Everything flush mounts with countersunk M2 hex flat-head screws.

Low Power: All modules can be shut down into a low-power state consuming only a few microamps, meaning your projects won't need on/off switches

Battery management: The base MCU board will support lipo charging and charge monitoring

USB programable with Arduino: The core MCU will be either the SAMD21 or possibly the Teensy 3.2. The core module will expose a USB port to the outside of your case.

Common libraries: Programming will be largely event-driven