This is a configuration file for the PNI WP800 16A WIFI Smart Plug in ESPHOME that allows you to connect it to Home Assistant locally.
The plug is powered by a hlw8012 power sensor and is based on the bk7231t chip (WB2S). So at least in theory, this setup file will work with any generic AliExpress WIFI smart socket that uses the WB2S chip.

The devices come from factory with a Tuya proprietary firmware that you need to rewrite using Tuya Cloudcutter https://github.com/tuya-cloudcutter/tuya-cloudcutter
I've calibrated the plug and it should be pretty precise in measuring the current and voltage, but you can do your own calibration directly in the .yaml

A tutorial on how you can flash your Tuya device with ESPHome you can find here: https://geekchronicles.ro/how-to-use-tuya-cloud-cutter-on-any-tuya-wifi-device/
