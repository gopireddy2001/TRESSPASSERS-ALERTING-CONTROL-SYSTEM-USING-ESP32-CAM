# TRESSPASSERS-ALERTING-CONTROL-SYSTEM-USING-ESP32-CAM

In this project we are going to make a motion sensor detector with photo capture using an ESP32-CAM.  When your   PIR sensor detects motion, it wakes up. The ESP32-CAM is deep sleep mode with external wake up enabled. When motion is detected, the PIR motion sensor sends a signal to wake up the ESP-32. It goes back to deep sleep mode until a new signal from the PIR motion sensor is received. When PIR sensor wakes up ESP32 –CAM it captures a picture and send to the administrator along with buzzer sound.
 
The ESP-32 does the above job. It receives the signals from the sensors, and this signal is operated under the control of software called Arduino (IDE). Also in addition the pictures captured by PIR sensor will be sending to the administrator and also triggers the buzzer thus makes this system a very user friendly
