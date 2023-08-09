1.Controlling an LED with a potentiometer

Description:
  -An LED is connected the STM32 DAC and the potentiometer is connected to the STM32 ADC.
   As the potentiometer is turned, the brightness of the LED is changed.

Device:
  -This code is built on the STM32 NUCLEO-F746ZG, this code should work for other 
   STM32s but the pin configurations may be different. Not all STM32s contain a 
   built in DAC which is required in this project. This project uses the ADC and
   the DAC.

Connections (applied to the STM32 NUCLEO-F746ZG only):
  NOTE: if separate power supply is used then ensure that the both GND are connected together,
  this ensures that the GND referance is the same.

  LED: 
    +ve to a 100 ohm resistor, which is connected to PA5
    -ve to GND

  Potentiometer: 
    +ve to 3.3V
    -ve to GND
    output to PA0
    
 
