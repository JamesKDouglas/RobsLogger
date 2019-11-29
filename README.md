# RobsLogger
This repository is for a data logger using a Particle Electron. 

The logger uses an SHT20 in a housing (called an SEN0227) to gather temperature and humidity data then records data to ThingSpeak and SD card. It sleeps between readings.

The LED is reduced in brightness so it is less irritating, but it still flashes upon wake. So a piece of electrical tape over the system LED is necessary.

Use the code in the Particle IDE by copying and pasting it. Libraries must be added through the IDE - the lines of code are not enough to include them.
