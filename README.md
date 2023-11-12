##################Creality Ender 3 S1 Pro Klipper Config###############
# This file contains pin mappings for the stock 2023 Creality Ender 3
# S1 Pro. To use this config check the STM32 Chip on the Mainboard,
# during "make menuconfig" select accordingly either the
# STM32F103 with "28KiB bootloader" or the STM32F401 with
# "64KiB bootloader" and serial (on USART1 PA10/PA9) for both.

# For a direct serial connection, in "make menuconfig" select
# "Enable extra low-level configuration options" and  Serial
# (on USART2 PA3/PA2), which is on the 10 pin IDC cable used
# for the LCD module as follows: 3: Tx, 4: Rx, 9: GND, 10: VCC

# Flash this firmware by copying "out/klipper.bin" to a SD card and
# turning on the printer with the card inserted. The filename
# must be changed to "firmware.bin"

# With STM32F401, you might need to put "firmware.bin" in a
# folder on the SD card called "STM32F4_UPDATE" in order to flash.

# See docs/Config_Reference.md for a description of parameters.

# A lot of the following Klipper macros were derived from Chris.
# His repository can be found here: https://github.com/rootiest/zippy-klipper_config 

# History:
# 20231105: initial setup
# 20231106: added fluidd
# 20231112: changed structure
