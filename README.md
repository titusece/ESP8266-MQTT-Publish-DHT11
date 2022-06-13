# ESP8266-MQTT-Publish-DHT11
Publish the temperature and humidity information


1) Run the MQTT broker in raspberry pi (host : 192.168.0.104)

2) Subscribe the humidity/temperature topic in raspberry pi board.

subscribe -t sensor/humidity

3) Upload the .ino file into NodeMCU board (ESP8266)

4) Connect DHT11 signal pin to D6 pin which is GPIO12, Vcc to 5V and GND to GND of NodeMCU board.

5) Power ON the NodeMCU board.

6) You can see the temp and humidity data in raspberry pi terminal.

