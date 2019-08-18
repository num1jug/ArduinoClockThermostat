# ArduinoClockThermostat

This is the sketch for a little LCD thermostat / clock.

It uses an Arduino Uno, an RTC ds1307, a ds18b20 digital temperature sensor, and a 16-pin LCD screen (16x2, using a 10K potentiometer for adjusting contrast).

The sketch requires the following libraries:
Wire.h
LiquidCrystal.h
OneWire.h
DallasTemperature.h
RTCLib.h
