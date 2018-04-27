# ESP-Weather-Underground-Sensor-Upload
Using an ESP32/ESP8266 to upload sensor data to your Weather Underground PWS


1. Choose your client to match your sensor, or use any as the template for your own sensor.

2. Copy the sketch to your IDE and include a copy of the 'system_variables.h file in the same folder. For the BME280 example, in your sketch folder should be:

 a. ESP_WU_Uploader_BME280_v01.ino

 b. system_variables.h 

3. Each client is already configured for the correct Weather Underground upload of sensor data.

4. Add your network SSID and PASSWORD.

5. Add your Weather Underground assigned PWS name and PASSWORD - note the password is for your WU account not the one for the new PWS.
