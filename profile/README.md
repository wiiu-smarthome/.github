# Wii U Smart Home Project
Welcome to the Wii U Smart Home Project! This project aims to make the Wii U integrate with the Internet of Things (IoT) and other home automation tools as much as possible.

You will need a [hacked console](https://wiiu.hacks.guide). Please note that this project is not affiliated with Nintendo in any way.

## Console Modules/Plugins
[Ristretto](https://github.com/wiiu-smarthome/Ristretto) is the [Aroma](https://aroma.foryour.cafe) plugin that enables network communication for IoT purposes to your console in Cafe OS.

[MQTTModule](https://github.com/wiiu-smarthome/MQTTModule) is a **work in progress** system module that runs a MQTT broker on the console. Soon, another plugin will be made that will actually provide the message topics.

## Home Hub Integrations
- [Homebridge](https://homebridge.io) - [homebridge-wiiu](https://github.com/wiiu-smarthome/homebridge-wiiu)

- [Home Assistant](https://home-assistant.io) - [ha-wiiu](https://github.com/wiiu-smarthome/ha-wiiu)

*If you have a SmartThings Hub or Hubitat Elevation, please let us know so we can make an integration!*

## Other
[python-wiiu-ristretto](https://github.com/wiiu-smarthome/python-wiiu-ristretto) is a Python library for interacting with Ristretto's API over the network.

## Future Possible Subprojects
- Binding for [openHAB](https://www.openhab.org)
  
- Implementing [Simple Service Discovery Protocol](https://en.wikipedia.org/wiki/Simple_Service_Discovery_Protocol) (SSDP)

- [uPNP](https://en.wikipedia.org/wiki/Universal_Plug_and_Play) - likely overkill, but would be cool
