# Temperature_Control_LAB_Alternative
Alternative version of the Arduino "Temperature Control LAB" shield for code testing
- Transistor BC338
- Heater element: 27R 5W resistor
- Temperature sensor LM35

![img](https://raw.githubusercontent.com/rtek1000/Temperature_Control_LAB_Alternative/main/PCB/Schematic.png)

--------

## Licence:

Note: This library is free software; you can redistribute it and/or modify it under the terms of the GNU Lesser General Public License as published by the Free Software Foundation; either version 2.1 of the License, or (at your option) any later version.

This library is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.

#### Hardware:
Released under CERN OHL 1.2: https://ohwr.org/cernohl

------

Test codes:
[sTune](https://github.com/Dlloydev/sTune)

![img](https://europe1.discourse-cdn.com/arduino/original/4X/d/a/c/dace8b3505c77cf28fa6e6d07bb2a02ef82bd720.png)

- This is an open loop PID autotuner using a novel s-curve inflection point test method. Tuning parameters are typically determined in about ½Tau on a first-order system with time delay. Full 5Tau testing and multiple serial output options are provided.

    - Compatible with [PID_v1](https://github.com/br3ttb/Arduino-PID-Library), [QuickPID](https://github.com/Dlloydev/QuickPID) and others
    - Serial output option for [PID Tuner](https://pidtuner.com/#/)
    - Tested using [Temperature Control Lab](http://apmonitor.com/pdc/index.php/Main/ArduinoTemperatureControl)

Source: https://forum.arduino.cc/t/stune-pid-autotune-library/941939

------

Temperature Control Lab - Original board:
- Transistor TIP31
- Heatsink
- Temperature sensor TMP36

![img](https://apmonitor.com/pdc/uploads/Main/tclab_schematic.png)

Source: https://scholarsarchive.byu.edu/cgi/viewcontent.cgi?params=/context/facpub/article/4888/&path_info=2020_park_tclab.pdf

