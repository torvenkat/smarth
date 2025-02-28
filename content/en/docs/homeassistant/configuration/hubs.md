---
title: "Hubs"
description: ""
lead: ""
date: 2023-01-27T08:08:57-05:00
lastmod: 2023-01-27T08:08:57-05:00
draft: true
images: []
menu:
  docs:
    parent: "configuration"
    identifier: "hubs-2fae682527f6bc4796d7cb2bfb184bb2"
weight: 119
toc: true
---

| Device                                                       | Quantity | Connection          | Integration                                                  | Notes                                                        |
| ------------------------------------------------------------ | :------: | ------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| [GoControl HUSBZB-1](https://www.amazon.com/GoControl-CECOMINOD016164-Linear-HUSBZB-1/dp/B01GJ826F8) |    1     | USB, Zigbee, Z-Wave | [Zigbee](https://www.home-assistant.io/integrations/zigbee/), [Z-Wave](https://www.home-assistant.io/integrations/zwave/) | Dual Zigbee and Z-Wave controller.  [See here for my notes](http://venkat.ca/passing-usb-to-guest-os-in-proxmox-virtual-environment/) on making this USB device available to Home Assistant running in a container under Proxmox VE. |
| [Lutron Smart Bridge 2](https://amzn.to/2GpRGEX)             |    1     | Ethernet            | [Lutron Caseta](https://www.home-assistant.io/components/lutron_caseta/) | Controls Lutron Caseta in-wall and plug-in light dimmers. A bit expensive, but one of the most reliable part of my home automation. |
| [Hue Hub v1](https://www2.meethue.com/en-ca/support/end-of-support-policy) |    1     | Ethernet            | [Philips Hue](https://www.home-assistant.io/components/hue/) | This controls all Hue, CREE, and GE Zigbee smart bulbs. Soon to be depreciated by Signify (the new brand name of Philips lighting).  I will migrate the bulbs to the above dual controller. |
| ESP-32, NodeMCU                                              |    1     | Wi-Fi, Bluetooth    | [ESPHome](https://www.home-assistant.io/integrations/esphome/) | Used as BLE tracker.   See Plants section for more information. |
| [Sonoff RF Bridge](https://sonoff.tech/product/accessories/433-rf-bridge) |    1     | Wi-Fi, RF 433 MHz   | [MQTT](https://www.home-assistant.io/integrations/mqtt/)     | Provides Wi-Fi bridge for RF 433 MHz sensors; Tasmota converted. |