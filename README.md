Pinoccio Capacitive Backpack
============================
Circuit, code and information for the Pinoccio capacitive backpack
Link to Pinoccio website: [Here](http://support.pinocc.io/hc/en-us/articles/202311914-Capacitive-Touch-Backpack)

Version 1 (current)
----------------------------
**Circuit:** [Here](https://raw.githubusercontent.com/Cisco25/pinoccio-capacitive-backpack/master/cap_backpack_circuit.PNG)

To view layout and order backpack from OSH Park: [Here](https://oshpark.com/shared_projects/NBBgAHbW)

P-I-N-O touches uses following pins:
 - A3, A4, A5, A6 (Send)
 - D8 (Receive)

Slider uses following pins:
 - A0, A1, A2 (Send)
 - D2 (Receive)


************
**GET STARTED**
************

**P-I-N-O capacitive touches:**
- Jump 4x resistors footprints R2 to R5
- Solder 4x 1MOhm resistors 0603 size onto C2 to C5 footprints
- Download and install ArduinoCapSense library: [Here](http://playground.arduino.cc/Main/CapacitiveSensor?from=Main.CapSense)
- Plug backpack and upload sketch CapTouch_PINO to scout using Arduino IDE (nightly build recommended by Pinoccio)
- Press one of the capacitive touch P, I, N or O: RGB led lights up with different colors!

**Slider:**
- Jump 3x resistors footprints R7 to R9
- Solder 3x 1MOhm resistors 0603 size onto C7 to C9 footprints
- Download and install ArduinoCapSense library: [Here](http://playground.arduino.cc/Main/CapacitiveSensor?from=Main.CapSense)
- Plug backpack and upload sketch CapTouch to scout using Arduino IDE (nightly build recommended by Pinoccio)
- Slowly move finger up and down on slider while pressing one of the capacitive touch P, I, N or O: RGB led brightness changes!

************
