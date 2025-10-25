# AT24CXX
  Device driver for AT24C16/32/64 EEPROMs.
  Tested using STM32F1/F4 MCUs. Hardware is abstracted using virtual tables and factory functions.

## Dependencies
  Use files from [STM32-Generic-Files] (https://github.com/greneruiz/STM32-Generic-Files):
    * Makefile
    * stm32_i2c.h, stm32_i2c.c
    * ggg_stm32_helper.h
    * stm32f103rb_startup.c, stm32f401xc_startup.c
    * stm32f1_linker.ld, stm32f4_linker.ld
