# Velux Remote Control

This is an ESPHome configuration to Control Velux Remote via ESP8266 , prefered Wemos D1.

With ESPHome you can control the device over Wifi and integrate it into Home Assistant.

More info @ https://esphome.io/

## Instructions
Create a secrets.yaml with your passwords

wifipassword: "wifipw"

otapassword: "otapw"

## Soldering
```
Wemos 3.3V + => Remote +

Wemos GND => Remote -

Wemos PIN D7 => Down Inner Circle

Wemos PIN D6 => Stop Inner Circle

Wemos PIN D5 => Up Inner Circle


```

![Solder](/images/solder.jpg)