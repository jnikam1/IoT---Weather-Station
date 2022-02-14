# IoT based Weather Station Using NodeMCU

Description:
IoT based weather station is used for
getting the temperature, humidity and pressure data
from BMP180, DHT11 sensors. Also, the data is
displayed on the OLED present in circuit so as to
monitor the data. The NodeMCU ESP8266 is used
for Wi-Fi module and to process the data. The
thingspeak web server is used to display the data
online.

Steps to run the code:

Step1: Connect the nodeMCU to the laptop
Step2: Open the Ardiuno IDE and select NodeMCU board with correct port.
Step3: NodeMCU uses Wi-Fi module to connect to the internet. In the code change the Wi-Fi 
       creds to your current Wi-Fi.
Step4: Create a open channel on thingspeak sever for sensors data to write on it.
       change the thingspeak api channel key to current channel created. 
Step5: Complie and upload the code to NodeMCU.
Step6: Check the output on OLED and Thingspeak server.
