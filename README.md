# GPIO_IOToggle
This example describes how to configure and use GPIOs through the HAL API.

On STM32F4xx-Nucleo RevC, PA05 
gpio pin is linked to LED2 - Green.
Main function conigures gpio on output pushpull mode, then in while loop, HAL 
toggles pin function is called.

In this example, HCLK is configured at 84 MHz.
