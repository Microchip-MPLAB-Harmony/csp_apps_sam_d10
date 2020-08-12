[![MCHP](https://www.microchip.com/ResourcePackages/Microchip/assets/dist/images/logo.png)](https://www.microchip.com)

# EIC Interrupt

This example application demonstrates how to generate interrupt using the EIC on switch press and indicate it through an LED.

## Description

The application registers an event callback with EIC Peripheral library and toggles an LED for every switch press event.

## Downloading and building the application

To download or clone this application from Github, go to the [top level of the repository](https://github.com/Microchip-MPLAB-Harmony/csp_apps_sam_d10) and click

![clone](../../../docs/images/clone.png)

Path of the application within the repository is **apps/eic/eic_led_on_off/firmware** .

To build the application, refer to the following table and open the project using its IDE.

| Project Name      | Description                                    |
| ----------------- | ---------------------------------------------- |
| sam_d10_xmini.X | MPLABX project for [SAM D10 Xplained Mini](https://www.microchip.com/DevelopmentTools/ProductDetails/PartNO/ATSAMD10-XMINI) |
|||

## Setting up the hardware

The following table shows the target hardware for the application projects.

| Project Name| Board|
|:---------|:---------:|
| sam_d10_xmini.X | [SAM D10 Xplained Mini](https://www.microchip.com/DevelopmentTools/ProductDetails/PartNO/ATSAMD10-XMINI)
|||

### Setting up [SAM D10 Xplained Mini](https://www.microchip.com/DevelopmentTools/ProductDetails/PartNO/ATSAMD10-XMINI)

- Connect the Debug USB port on the board to the computer using a micro USB cable

## Running the Application

1. Build and Program the application using its IDE
2. LED toggles on every switch press

Following table provides the LED name:

| Board      | Switch Name | LED Name |
| ---------- | ---------| ------------|
| [SAM D10 Xplained Mini](https://www.microchip.com/DevelopmentTools/ProductDetails/PartNO/ATSAMD10-XMINI) | SW0 | LED0 |
||||
