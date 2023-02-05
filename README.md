# TFT_eSPI Setups
Setup directory and files for TFT_eSPI according to the [tips section](https://github.com/Bodmer/TFT_eSPI#tips) of the readme for [TFT_eSPI](https://github.com/Bodmer/TFT_eSPI) to support a ST7789 and Kalinco p22 board. This is a different directory, TFT_eSPI_smartwatch_Setup, as not to overwrite TFT_eSPI_Setups, if you created one. After an upgrade simply edit the User_Setup_Select.h file to point to your custom setup file e.g.:
```
#include <../TFT_eSPI_Smartwatch_Setups/kalinco_p22_setup.h>
```


Also, an updated ST7789_Init.h file without the legacy backlight code, which you need to copy into TFT_eSPI/Drivers directory, overwriting the existing one.
