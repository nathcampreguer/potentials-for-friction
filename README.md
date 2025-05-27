# potentials-for-friction
Suplementary code of the article "Potentials for Friction: Exploring the Design Space Between Playfulness and Agonism"

## Arduino Cloud Config

### Thing 1: printer-terminal
Associated device: Arduino Uno R4 WiFi

Variables:

|Name | Type | Permission | Update Policy | Note|
|----------|----------|----------|----------|----------|
|cup_id | Character string | Read and write | On change | RFID ID received from rfid-terminal, triggers the printer.|
|message_log | Character string | Read only | On change | Used for the dashboard|
|time_log | Time | Read only | On change | Used for the dashboard|

### Thing 2: rfid-terminal
Associated device: Arduino Nano 33 IoT

Variables:

|Name | Type | Permission | Update Policy | Note|
|----------|----------|----------|----------|----------|
|cup_id | Character string | Read only | On change | RFID ID read by the RC522 module. |
