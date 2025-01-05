# ESP32 Lightbulb example that works with Hue bridge

This is Espressif's [HA_color_dimmable_light](https://github.com/espressif/esp-zigbee-sdk/tree/a943a9118e9ad110e2641e1187fd4c5d533f8a06/examples/esp_zigbee_HA_sample/HA_color_dimmable_light)
**that will be**
adjusted to successfully link against Hue bridge.

Mind you, you'll need to adjust the trust center key.

Details in my [Zigbee: Hue-llo world!](https://wejn.org/2025/01/zigbee-hue-llo-world/)
blog post.

To compile:

``` sh
./in-docker.sh idf.py set-target esp32-c6 build
```

To clean up:

``` sh
./in-docker.sh rm -rf build dependencies.lock managed_components/ sdkconfig
```
