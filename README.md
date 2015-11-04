# FrSkyTelemetry
MAVLink information and additional temperature sensors are displayed on FrSky Taranis using Arduino.
This solution uses Arduino NANO to convert MAVLink telemetry protocol to FrSky smart port protocol.
Arduino plays a role of bridge between the telemetry UART port of APM and smart port of FrSky radio receiver (X8R, X6R, X4R).
Communication between Arduino and MAVLink source (APM) is implemented via hardware UART of Arduino.
FrSky smart port is connected to a digital pin that SoftwareSerial drives.
Besides MAVLink, Arduino provides 2 temperatures meaused by NTC termistors for smart port.
MAVLink and temperatures are displayed on FrSky Taranis radio receiver using Lua scripts.      
There is a schematic drawing of Arduino pins, NTC termistors, MAVLink and smart port.

 
