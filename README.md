# STM32H755 Blinking LED Project

A simple blinking LED project for the STM32H755 dual-core microcontroller.

## Hardware
- STM32H755 Development Board
- LED connected to GPIO pin

## Features
- Dual-core ARM Cortex-M7 and Cortex-M4
- Basic GPIO control
- LED blinking functionality

## Build Instructions
1. Open the project in STM32CubeIDE
2. Build for both CM4 and CM7 cores
3. Flash to the target device

## Project Structure
- `CM4/` - Cortex-M4 core source files
- `CM7/` - Cortex-M7 core source files
- `Common/` - Shared source files
- `Drivers/` - HAL and BSP drivers
- `Blinking_Led.ioc` - STM32CubeMX configuration
