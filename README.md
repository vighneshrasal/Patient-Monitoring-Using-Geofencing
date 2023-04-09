# Patient-Monitoring-Using-Geofencing
A Device made using Arduino that will automatically send a SMS to registered phone no. When the device will leave the Virtual Vicinity to alarm the Administrator that the Patient has left the perimeter. It targets Dementia Patient who have or going to memory loss and are strugling to keep up with basic everyday tasks.

Hardware Used:
1. Arduino Nano
2. GSM Module 
3. GPS Module
4. Piezo Buzzer
5. 5V Battery

Implementation: 
1. The Arduino board controls the actions of all other devices
2. The GSM module is fitted with a SIM card, it is used to stay connected to the Telecom network because it need to send SMS to registered phone no.
3. The GPS Module is constantly tracking the Geographic Location using the Latitudes and Longitudes of the current Location.
4. When the device leaves the already defined vicinity the GSM triggeres to send the SMS and Buzzer sounds alarm to warn the Patient.
