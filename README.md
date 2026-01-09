# STM32 ADC triggered by Timer using DMA and UART

This project implements ADC data acquisition on STM32F103C8 (Blue Pill)
using a 100 Hz timer trigger. ADC conversion is triggered on timer overflow,
data is transferred using DMA, and UART transmission logic is implemented.

## Features
- TIM configured for 100 Hz
- Timer-triggered ADC conversion
- DMA-based ADC data transfer
- UART transmission logic (HAL)
- STM32CubeIDE + HAL based project

## Notes
- Bare-metal not used
- UART output logic is implemented in code
- Project tested up to build stage
