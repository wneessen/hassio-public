# Home Assistant - OctoPrint MQTT Integration

## Requirements
- [OctoPrint](https://octoprint.org/)
- [OctoPrint MQTT Plugin](https://github.com/OctoPrint/OctoPrint-MQTT)
- [OctoPrint MQTT-HA Plugin](https://github.com/cmroche/OctoPrint-HomeAssistant)

## Installation
- Install the two OctoPrint plugins through the OP-Plugin manager
- Follow the configuration instructions of both plugins to integrate with your MQTT instance
- Once the plugin has connected to your MQTT instance, your HomeAssistant should see the new entities in the MQTT-Integration tab
- You can now use the sensors to your liking
- Use the provided .yml-files as examples to integrat with your Lovelace UI