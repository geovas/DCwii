DCwii
=====

WLtoys V949 alternative MultiWii 2.0 ready main board
-----

**CAD-system:**            
NOVARM DipTrace Version 2.3.1.0: http://www.diptrace.com/         
Project Current Directory: **C:\my3d\quad\**

**Directories:**
- 3DS: 3D models
- IMG: Images and photos
- OUT: Schematics and PCB
- PCB: PCB library
- SCH: Schematics library

**List of components:**
- R1, R2, R7, R8, R9, R10, R11, R12, R15 - 1.0 kOhm SMD 0805 Resistor
- R3, R4, R5, R6, R16, R17 - 10 kOhm SMD 0805 Resistor
- R13, R14 - 330 Ohm SMD 0805 Resistor
- C1, C2 - 1.0 uF SMD 0805 Ceramic Capacitor
- Q1, Q2, Q3, Q4 - SI2302 FET SOT-23
- VD1, VD2 - SMD LED
- VD3, VD4, VD5, VD6 - SMD Schottky Diode
- XN1: Front Left motor
- XN2: Front Right motor
- XN3: Rear Left motor
- XN4: Rear Right motor
- XN5: JST Female connector (in my config it's connected to Turnigy Nano-Tech 1S 600mAh)
- X1: connected to Rx (in my config it's Turnigy RX7000S)
- X2: opened
- X3: closed by jumper (or wire)
- X4: connected to Voltage Booster (in my config it is Turnigy Voltage Booster for servo & Rx)
- DD1: Arduino Pro Mini 8MHz 3.3v (from ebay). IMPORTANT! I2C pins may vary in you Arduino!
- DD2: GY-521 (MPU-6050 based board) or handmade MPU3050 board (I'm using second).


