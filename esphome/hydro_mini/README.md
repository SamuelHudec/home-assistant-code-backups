# Mini Hydrophonia

For the pilot version, I chose the LaskaKit development microESP32 for its battery/solar charging solution
 and a compatible mosfet board. Last free GPIO pins will serve for water level senzor and I2C port (uŠup) for 
temperature and humidity senzor.

## Pilot Components
- [Board](https://www.laskakit.cz/laskakit-microesp/)
- [MOSFET](https://www.laskakit.cz/laskakit-microesp-mosfet-shield/)
- [Battery](https://www.laskakit.cz/ehao-lipol-baterie-6060100-5000mah-3-7v/)
- [Solar (sold)](https://www.laskakit.cz/solarni-panel-5v-7-5w-s-usb/)
- [Pump](https://www.laskakit.cz/ponorne-mini-cerpadlo-ultra-tiche-dc-3-6v-120-l-h/)
- [Water level Senzor](https://www.laskakit.cz/arduino-plovakovy-senzor-vodni-hladiny/)
- [Temperature Senzor](https://www.laskakit.cz/laskakit-sht40-senzor-teploty-a-vlhkosti-vzduchu/)
- [uŠup](https://www.laskakit.cz/--sup--stemma-qt--qwiic-jst-sh-4-pin-kabel-5cm/)


## How to compile and install SW using ESPhome Web

This project can be compiled and flashed directly from a YAML file using ESPHome Web. 
No Home Assistant or local ESPHome installation is required.

**Steps**
1. Prepare your YAML file
2. [Open ESPHome Web](https://web.esphome.io/?utm_source=chatgpt.com)
3. Connect your ESP32-C3 and follow the instructions on web
4. Compile & Flash
  - Click Install → Pick a YAML file.
  - Upload your yaml.
  - ESPHome Web will compile it into a .bin firmware.
  - Once done, click Install to flash it to the ESP32-C3.
