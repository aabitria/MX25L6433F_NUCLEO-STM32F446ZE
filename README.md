# External Loader for NUCLEO-F446ZE / X-NUCLEO-GFX01M1

This STM32 external loader is designed for the combination of NUCLEO-F446ZE and the MX25L6433F SPI NOR in X-NUCLEO-GFX01M1.  This can also be used as a basis for other F4xx-MX25 boards' external loader.

SPI2 is used for communication between the MCU and the SPI NOR (MX25L6433F), using PB9, PB13, PC2, PC3 for SPI2_NSS, SPI2_CLK, SPI2_MISO, and SPI2_MOSI respectively.

The resulting .stldr file will be used in STM32CubeProgrammer or in CubeIDE during debugging when files are being flashed.

Based on:
https://controllerstech.com/w25q-flash-series/

The initial EL files were obtained from:
https://github.com/STMicroelectronics/stm32-external-loader
