# Waveshare ESP32-P4-WIFI6-Touch-LCD-7B

7-inch 1024x600 Waveshare ESP32-P4 + ESP32-C6 hosted Wi-Fi panel for EspControl.

This device profile is based on the EspControl Guition 7-inch 1024x600 layout, but changes the hardware layer for the Waveshare ESP32-P4-WIFI6-Touch-LCD-7B:

- MIPI DSI model: `WAVESHARE-ESP32-P4-WIFI6-TOUCH-LCD-7B`
- Backlight PWM: GPIO32, inverted
- GT911 touch: I2C GPIO07/GPIO08, reset GPIO23
- Wi-Fi: ESP32-C6 hosted over SDIO GPIO54/19/18/14/15/16/17

The UI layout reuses the existing EspControl 15-button 5x3 grid.
