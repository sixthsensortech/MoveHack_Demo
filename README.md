

# Following are the executable (.hex) files used to program different Hardware modules

1. Gyroscope Module- "ACC_20012016.hex" - this module monitors the vehicle path in order to avoid false alarms. 
2. ECU Module - "ECU_01_01_02_36.hex" - The heart of the system, where it consists of algorithms and collects data of driving pattern and sends it to the server. 
3. HMI Module - "LED_00_01_01_08.hex "  - the hunam machin interface. 



# Following are the executable files of Android applications

1. Sixth Sensor App - "6thSense_v2.5.apk"
   This app is used to connect with ECU and Server. App Collects data from vehicle ECU and uploads on Server and vice-versa
   This app is used for monitoring as well as for ECU feature configuration and control.
2. Driver drowsiness App - "app-debug.apk"
   This app is developed to use the front camera and using image processing detects if the driver is sleepy while driving and then alerts the driver with sounds and sends the data via cloud to the server. If the driver is sleepy for more than 5 seconds then the system also cuts off the accelrator to avoid accidents. 


# Following executable file is used for monitoring and configuration of ECU parameters if System is without Android phone.

1. Windowns application - "setup.exe"
   This executable file is used on windows based system for configuration and monitoring of vehicle by technicians.
   This app can be used to configure various paramenters of vehicle and also to fetch offline data stored during trip. 
