# F1MV-Lights-MQTT
## Blueprint for the MQTT Integration of F1MV-Lights Multiviewer Integration

Do additional actions in Homeassistant, when F1MV-Lights-Integration triggers an event. 

F1MV-Lights-Integration is a great integration to F1 Multiviewer.
https://multiviewer.app/ 

With the F1MV-Lights-Integration you can set all your controllable lights to a specific color, when different events occur (e.g. different flag colors)
Take a look here for further information.
https://github.com/JustJoostNL/F1MV-Lights-Integration

This Blueprint is based on the MQTT integration and will automatically trigger your lights or group of lights you setup.\n
Note: You need to setup the MQTT Integration in F1MV-Lights-Integration!

<b>Please make sure to send ContolType 'On' with all your actions, else the event will be not send over mqtt.</b>



[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fmkcologne%2FF1MV-Lights-MQTT%2Fblob%2Fmain%2FF1MV-Lights-MQTT.yaml)
