# Home Automation

Maintained a Home Assistant instance across multiple apartments and homes over the years, continuously expanding my smart home integrations and automation capabilities.

* Smart Home Integration: Integrated a wide range of compatible devices and services into Home Assistant to create a unified smart home ecosystem.
* Everyday Automation: Automated routine tasks, including vacuuming and monitoring door status to help ensure doors are closed and locked.
* Accessibility-Focused Automation: Implemented visual alerts, including flashing doorbell notifications and smoke alarm alerts, to make my home more accessible and deaf-friendly.

## Smart Home Design Principles

* **Local-First Control**: Avoid cloud dependencies whenever possible, prioritizing locally controlled devices and integrations. Cloud connectivity is acceptable when a practical local alternative is unavailable, such as with certain robot vacuums or HVAC systems.
* **Independent Operation**: Ensure essential device controls remain functional even when Home Assistant is offline. For example, smart switches should continue to operate manually without relying on Home Assistant.
* **Portability**: Favor devices and installations that are easy to install, remove, and relocate when moving between apartments or homes.

## Key Integrations & Automations

### Home Automation & Convenience

- **Automated Cleaning:** Schedule a SwitchBot K11+ robot vacuum to clean automatically.
- **Smart Lighting & Switches:** Use ESPHome-powered smart switches for locally controlled lighting and device management.
- **Garage Door Control:** Integrate a Shelly 1 One-Relay with an existing garage door opener to enable remote control and monitor door position using a wired contact sensor.
- **Door & Garage Alerts:** Receive notifications when the front door remains unlocked or the garage door remains open for more than five minutes.

### Environmental Monitoring
- **Whole-Home Temperature Monitoring:** Deploy Govee H5110 Bluetooth temperature sensors throughout the home to monitor temperature variations and evaluate insulation effectiveness.
- **Refrigerator & Freezer Monitoring:** Use Govee H5108 sensors to trigger alerts when temperatures exceed configured thresholds.
- **Filament Storage Monitoring:** Monitor temperature and humidity inside 3D-printing filament storage containers using Aqara WSDCGQ11LM sensors.

### Energy Management
- **Energy Consumption Monitoring:** Track electricity usage using Shelly 3EM energy meters, smart plugs, and Enbrighten 500S smart switches (models 14285 / ZW4007).

### Security & Notifications
- **Occupancy-Aware Security Alerts:** Use motion sensors to notify me of detected activity while the household is away.

### 3D Printing & Electric Vehicle Charging
- **3D Printer Status Notifications:** Receive updates on 3D printer status through Home Assistant integrations.
- **EV Charging Management:** Integrate an OpenEVSE Advanced Series 48A Level 2 NACS charging station to schedule charging sessions and monitor power consumption for my Rivian R2.

## Software Stack

The following software powers my home automation environment, providing device integration, communication between protocols, and centralized management.

- **[Home Assistant](https://www.home-assistant.io/)** — Central home automation platform for integrating smart devices, managing automations, and controlling household systems.
- **[Zigbee2MQTT](https://www.zigbee2mqtt.io/)** — Bridges Zigbee devices to MQTT, enabling Home Assistant to integrate and manage compatible devices.
- **[Zwave2MQTT](https://github.com/OpenZWave/Zwave2Mqtt)** — Bridges Z-Wave devices to MQTT for integration with Home Assistant.
- **[Fleet for ESPHome](https://github.com/weirded/fleet-for-esphome)** — Provides a centralized web interface for managing ESPHome devices, including deployment and firmware updates.

## Diagram

[![HomeAutomation_Diagram](/images/diagram.jpg)](/images/diagram.jpg)
