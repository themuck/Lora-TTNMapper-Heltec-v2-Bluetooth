# Lora-TTNMapper-Heltec-v2-Bluetooth

based on this https://github.com/noppingen/Lora-TTNMapper-Heltec-v2 sketch i add a Bluetooth funktion to edit the spreading factor 7/8/9/10/11/12 via an Android app. And you can select channels. 

You have to set the MQTT settings for the application in the TTN setup. And define your RX & TX Pins for the GPS, enable "Skip payload encryption and decryption" in device Application layer settings. Becouse the massage counter did nor work in the Heltec Node.  

The Android app read the same BT massages like the OLED Display and catch the MQTT Data to calculate und visualize the position to the Gateway. You can safe a log file with the GPS and Signal Data. It more or less works like the TTN Mapper app, less visual effects but more Data. 

The App is bulid with MIT App Inventor.
