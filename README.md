# Home Assistant - Secondary Instance

The only task of this instance is to forward sensor data from a SystemAir VSR 150/B to my main Home Assistance Instance.

## Architecture

SystemAir VSR 150/B --Modbus--> Home Assistant (RPI 3b+) --MQTT--> Home Assistant Core (Linux)
