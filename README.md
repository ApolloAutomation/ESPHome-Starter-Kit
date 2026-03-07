# Apollo ESK-1 Starter Kit

![Apollo ESK-1](ESK-1PCB.png)

The ESK-1 is designed in collaboration with the **Open Home Foundation**. A portion of the profits from each ESK-1 sold goes directly to the OHF team to support their work on Home Assistant, ESPHome, Music Assistant, and other open-source smart home projects.

## Key Features

**ESP32-C6 Based:** Built on the ESP32-C6-mini module with Wi-Fi, Zigbee, and Thread radios for versatile smart home connectivity.

**Zigbee & Thread Support:** Dual antennas for Zigbee and Thread protocols. Supports Matter over Thread for future-proof smart home integration.

**USB-C Power:** USB-C port for easy power and programming.

**Expansion Ports:** Two 13-pin FPC cable ports allow you to connect and power virtually any sensor or accessory.

**Onboard Controls:** Boot and Reset buttons for easy flashing and debugging.

**Battery Powered:** Includes battery connector with MAX17048 fuel gauge for accurate voltage and percentage monitoring.

**Deep Sleep Support:** Configurable deep sleep duration for extended battery life. Wakes periodically to report sensor values and returns to sleep.

**RGB Status LED:** Onboard fully addressable WS2812 LED indicates battery status:
- Red: Battery below 40%
- Yellow: Battery between 40-79%
- Green: Battery 80% or above

**Prevent Sleep Toggle:** Easily disable deep sleep via Home Assistant for OTA updates or continuous monitoring.

**Accessory Power Control:** GPIO-controlled power rail for connected accessories, automatically disabled during deep sleep to conserve battery.

## What's in the Kit

- **ESK-1 Main Board** - ESP32-C6 with dual FPC expansion ports
- **PIR Sensor** - Motion detection
- **Temperature/Humidity Sensor** - Environmental monitoring
- **Notification Puck** - LED and piezo buzzer PCB for visual and audio alerts
- **Button** - Physical input for triggering automations

## Pinout

| Function | GPIO |
|----------|------|
| I2C SDA | GPIO21 |
| I2C SCL | GPIO20 |
| RGB LED | GPIO5 |
| Accessory Power | GPIO4 |

## ESPHome Integration

The ESK-1 is designed for use with ESPHome and Home Assistant. See the `Integrations/ESPHome/` folder for the YAML configuration.

## Links

Discord (Support/feedback/discussion/future products): [http://dsc.gg/ApolloAutomation](http://dsc.gg/ApolloAutomation)
Shop: [https://apolloautomation.com](https://apolloautomation.com)
Wiki: [https://wiki.apolloautomation.com](https://wiki.apolloautomation.com)
Open Home Foundation: [https://www.openhomefoundation.org](https://www.openhomefoundation.org)
