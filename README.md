![Renesas](https://github.com/buglabs/Synergy-Starter-Kit/blob/master/Pictures/renesas.png)

# Renesas IoT Sandbox  S3A7 Synergy Starter Kit 
## Binary for Data Monitoring, powered by Bug Labs, Inc. 

Repository for the Renesas IoT Sandbox, Synergy Starter Kit, Data Monitoring powered by Bug Labs Software, Code, and Guide

**Table of Contents** 
- [Getting Started](#getting-started)
	- [Install J-Link Software](#install-j-link-software)
	- [Connect Kit to Computer](#connect-kit-to-computer)
- [Programming](#programming)
	- [Windows](#windows)
	- [Source Code Details](#source-code-details)
	- [Dweet Library](#dweet-library)
	- [Dweet Client Examples](#dweet-client-examples)
- [Troubleshooting Notes](#troubleshooting-notes)
- [Helpful Links](#helpful-links)

## Getting Started

In order to use the Data Monitoring platform, you must first download the renesas.dweet.io binary onto your S3A7 Synergy Starter Kit.
You will need the following:

* Renesas S3A7 Fast Prototyping kit with JLink connector
* Download “J-Link Software and Documentation Pack” from https://www.segger.com/downloads/jlink if not already installed on your computer
* Program image (.srec format)
* Windows or Mac computer

### Install J-Link Software

Download file from above. Remember where you save the execuitable file

### Connect Kit to Computer

Connect the debugger to your computer and S3A7 kit like below

![ren1](https://github.com/buglabs/Synergy-Starter-Kit/blob/master/Pictures/S3A7/ren1.jpg)

![ren2](https://github.com/buglabs/Synergy-Starter-Kit/blob/master/Pictures/S3A7/ren2.jpg)

![ren3](https://github.com/buglabs/Synergy-Starter-Kit/blob/master/Pictures/S3A7/ren3.jpg)


Finally, connect one USB to power the S3A7 board and a second USB from the JLink programmer to your PC.


## Programming
### Windows

Make sure J-Link drivers were installed

![J-Link driver](https://github.com/buglabs/Synergy-Starter-Kit/blob/master/Pictures/S3A7/J-Link%20driver.png)

Open J-FLash Lite Program

![J-Flash Lite](https://github.com/buglabs/Synergy-Starter-Kit/blob/master/Pictures/S3A7/J-Flash%20Lite.png)

Click OK on the popup

![J-Flash popup](https://github.com/buglabs/Synergy-Starter-Kit/blob/master/Pictures/S3A7/J-Flash%20popup.png)

Set settings to: R7FS3A77C, JTAG, 6000

![ren7](https://github.com/buglabs/Synergy-Starter-Kit/blob/master/Pictures/S3A7/ren7.png)

![ren8](https://github.com/buglabs/Synergy-Starter-Kit/blob/master/Pictures/S3A7/ren8.png)

Add the Binary file

![ren9](https://github.com/buglabs/Synergy-Starter-Kit/blob/master/Pictures/S3A7/ren9.png)

Open binary, select program, click “Program Device”

![ren10](https://github.com/buglabs/Synergy-Starter-Kit/blob/master/Pictures/S3A7/ren10.png)

![ren11](https://github.com/buglabs/Synergy-Starter-Kit/blob/master/Pictures/S3A7/ren11.png)

Restart Board - Congrats!

## Troubleshooting Notes
* The following popup means the J-Link drivers were not successfully installed. Please install again.

![ren12](https://github.com/buglabs/Synergy-Starter-Kit/blob/master/Pictures/S3A7/ren12.png)

## Helpful Links
* Freeboard Open Source Repo: (https://github.com/Freeboard/freeboard)

![BUG logo gif](https://github.com/buglabs/Synergy-Starter-Kit/blob/master/Pictures/BUG_logo_gif.gif)
