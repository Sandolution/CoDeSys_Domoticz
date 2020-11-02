# CoDeSys_Domoticz
CoDeSys library for connection with the Domoticz Home Automation System.

Works by calling the Domoticz API via HTTP with multiple connections at the same time (default: 8) and parsing and distributing the data among the configured slaves.
To have state changes (e.g. pushbuttons, door contacts, etc.) processed quickly (instead of waiting for HTTP update), MQTT is also used to receive updates.
Because of the relatively 'simple' configuration of Domoticz Mosquitto hardware, the library mostly relies on it's HTTP processing (MQTT is not used).

More written explanation coming later...
