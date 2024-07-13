This code is used for voltage level measurement at 0-24V interval via ADC module of STM32.
While scaling 0-24V interval to 0-3.3V interval (3.3V is maximum voltage output level of STM32 pins), linear interpolation is used for decrease the error percentage.
STM32F303RE nucleo board is used.
Using lower sampling rate is advisable.  
 
