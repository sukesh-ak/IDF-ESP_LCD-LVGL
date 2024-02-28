# IDF-ESP_LCD-LVGL
How to use ESP_LCD component with LVGL component from `Espressif` component repository

LCD Driver   : ESP LCD ST7796 SPI ([ESP Registry Link](https://components.espressif.com/components/espressif/esp_lcd_st7796/versions/1.2.1?language=en)) - Only v1.0.0 is supported for ESP32  
TOUCH Driver : ESP LCD Touch FT5x06 Controller ([ESP Registry Link](https://components.espressif.com/components/espressif/esp_lcd_touch_ft5x06))  
LVGL : v9.x ([ESP Registry Link](https://components.espressif.com/components/lvgl/lvgl)) using custom `lv_conf.h` => [CMakeLists.txt](CMakeLists.txt)  
ESP_LVGL_PORT : From `esp-bsp` with bug fix till latest version is available at ESP Registry [here](https://components.espressif.com/components/espressif/esp_lvgl_port). 

