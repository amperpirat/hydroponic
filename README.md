# hydroponic
indoor hydroponic system to grow herbs and salad

# Hardware
* ESP32 based PCB including DC/DC converter (5-60V input) and 2 relais
* 12V self-priming waterpumps (1-2l/min)
* GPIO 16 is wired to the emptying pump
* GPIO 17 is wired to the filling pump

# Software
* The hydroponic control is based on the home automation software espEASY (https://github.com/letscontrolit/ESPEasy/releases). Detailled documentation is available here: https://espeasy.readthedocs.io/en/latest/
* The control itself is based on rules (can be found as three files in the repo)
* configuration of devices is mandatory to be exactly the same
* MQTT for changing the timings, enable and disable the timer as well as monitoring the device
* configuration pictures can be found under pictures

