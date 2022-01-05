# Interfacing_STM32_BLE-dongle
Create a Bluetooth Low Energy (BLE) project with an STM32 microcontroller and BlueIO.


We'll learn how to make a BLE project with an STM32 microcontroller and BlueIO in this tutorial. The project is a simple demonstration of how to set up an STM32Cube project as a USB CDC Host capable of talking with the BleuIO Dongle in a short amount of time.

The STM32 will identify a BleuIO Dongle when it is connected to the Nucleo board's USB connection. The BleuIO Dongle will then accept one of three UART inputs and transmit one of three preprogrammed commands according on the input.
