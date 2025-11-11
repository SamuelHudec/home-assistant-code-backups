# ESP home

My favorite part of playing with HA. Here you can find my attempts, beginnings, fails
 and successes in creating my own but also replicated (and modified) automations.


[Usefull manual for adding new device in home assistant](https://esphome.io/guides/getting_started_hassio/)

## How to compile and install SW using ESPhome Web

This project can be compiled and flashed directly from a YAML file using ESPHome Web.
No Home Assistant or local ESPHome installation is required.

**How to do:**
1. Prepare your YAML file
2. [Open ESPHome Web](https://web.esphome.io)
3. Connect your ESP32-C3 and follow the instructions on web
4. Compile
  - Navigate to folder where you store `your.yaml`
  - in terminal run: `docker run --rm -v "${PWD}":/config -it ghcr.io/esphome/esphome compile your.yaml`
  - bin you can find: `.esphome/build/your/.pioenvs/your/firmware.bin`
5. Flash
  - Click Install → Pick a Bin file.
  - Upload your yaml.
  - ESPHome Web will compile it into a .bin firmware.
  - Once done, click Install to flash it to the ESP32-C3.
