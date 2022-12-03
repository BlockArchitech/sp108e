# sp108e

Integrates SP108E Wi-Fi 'LED SHOP' controllers into Home Assistant.

Tested using:
- SP108E (BTF-LIGHTING brand)
- WS2811 String


built using https://github.com/home-assistant/example-custom-config/tree/master/custom_components/example_light
and https://github.com/kylezimmerman/pyledshop as a base.

added conifg_flow to support adding devices via the ha ui. host (ip address) and name are required
for each controller.

### Installation

Copy or clone into `<config_dir>/custom_components/sp108e_ws2811/`.

Use the config flow via the UI to setup.

### Note

I've used other LED strips with this (in fact - the original project uses as WS2815, this fork uses WS2811) and they do work, however Any strip that supports the SP108E should work, and if it doesn't it is simply a limitation of the hardware.
