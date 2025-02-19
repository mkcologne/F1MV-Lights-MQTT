# F1MV-Lights-MQTT
Blueprint for the MQTT Integration of F1MV-Lights Multiviewer Integration

Do additional actions in Homeassistant, when F1MV-Lights-Integration triggers an event. 

F1MV-Lights-Integration is a great integration to F1 Multiviewer.
https://multiviewer.app/ 

With the F1MV-Lights-Integration you can set all your controllable lights to a specific color, when different events occur (e.g. different flag colors)
Take a look here for further information.
https://github.com/JustJoostNL/F1MV-Lights-Integration

This Blueprint is based on the MQTT integration and will automatically trigger your lights or group of lights you setup.\n
Note: You need to setup the MQTT Integration in F1MV-Lights-Integration!

<b>Please make sure to send ContolType 'On' with all your actions, else the event will be not send over mqtt.</b>

