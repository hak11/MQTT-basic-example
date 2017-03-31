# MQTT-basic-example
basic mqtt protocol

thanks for this video https://www.youtube.com/watch?v=PgsH43Tpqjc

this code special for fixing error :

ESP8266_SimpleMQTT.ino:25: error: 'callback' was not declared in this scope
 PubSubClient client(MQTT_SERVER, 1883, callback, wifiClient);

in Arduino IDE new version (me : 1.8.1)
