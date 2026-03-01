# Dual-Sensor-Motion-and-Temperature
 
 This project contains files for:
  - hardware:
    - ESP32 based microcontroller (M5 Atom Lite)
    - microwave motion sensor 
    - temperature and humidity sensors
  - firmware:
    - ESPHome YAML script specifying the device behaviour and its integration with Home Assistant
  - Home Assistant configuration:
    - automation scripts for motion detection and management of lights
    - user interface specification (YAML files)
  - Real-life use case:
    - as described in the comments withing the files.

Use case:
 - self-designed and produced intelligent sensor that detects motion, measures temperature and humidity
 - precise motion detection (class-better than offered by PIR sensors)
 - automated lights on, delayed lights off
 - specific case for detecting motion / lack of montion and switching on/off lights in a space, where no hands might be available to operate light switches

Learning opportunities:
- physics (microwaves!)
- electronics
- low-level / low-code programming
- Home Assistant configuration and scripting
