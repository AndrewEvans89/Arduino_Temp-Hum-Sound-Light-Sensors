# Arduino_Temp-Hum-Sound-Light-Sensors
Detecting Temperature, Humidity, Sound, and Light using an Arduino Uno and multiple sensors.

Harware Being Used:
1. Arduino Uno
2. Electret Microphone Amplifier - MAX4466 with Adjustable Gain
3. AM2302 (wired DHT22) temperature-humidity sensor
4. OSEPP Light Sensor

Wiring For:

    AM2302:
    Data (yellow) to Pin 2
    Power (red) to 5v
    Ground (black) to GND
    
    OSEPP:
    Ground (-) to GND
    Power (+) to 5v
    S to A1
    
    Electret:
    Ground (GND) to GND
    Power (Vcc) to 3v
    OUT to A0
   
I have one side of the breadboard powered to 5v and the other to 3v.
