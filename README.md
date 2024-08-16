#ClockCompanion

A companion application for an ESP32 run alarm clock. It connects to the ESP32 DevKit1 using BLE. It can set the alarm volume, alarm length before auto shut-down and alarm times. It will also communicate wifi details such as network name and network password. This will then be utilized by the ESP32 to fetch the weather and periodically calibrate itself (Based on the users region, if the user so choses to do so).
