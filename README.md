![Renesas](https://github.com/buglabs/Synergy-Starter-Kit/raw/master/Pictures/renesas.png)

# Renesas IoT Sandbox  S5D9 Synergy Starter Kit 
## Data Monitoring, powered by Bug Labs, Inc. 

Repository for the Renesas IoT Sandbox, Synergy Starter Kit, Data Monitoring powered by Bug Labs Software, Code, and Guide

**Table of Contents** 
- [Getting Started](#getting-started)
- [Using Freeboard](#using-freeboard)
- [Troubleshooting Notes](#troubleshooting-notes)
- [Helpful Links](#helpful-links)

## Getting Started

### Step 1 

* Take board out of box

### Step 2 

* Connect USB cable to laptop

	* Board comes up as USB drive
	* USB also provides power to the board

### Step 3 

* Open RunProgram.txt 

	* Edit the “program name” to say “Remote Sensor Monitoring”
	
		* Where it says “run” and “program name” 

### Step 4 

* Connect board to Ethernet

### Step 5 

* Open ThingName.txt 
* Copy Thing Name (S5D9-XXXX) into the field on the [Data Monitoring developer area](https://renesas.dweet.io/)

![sandbox2](https://github.com/buglabs/Synergy-Starter-Kit/raw/master/Pictures/sandbox2.PNG)

* Click Try it now!

### Step 6 

* A page will appear with live sensor data streaming from the board (Data streams once per second)

![S5D9 follow](https://github.com/buglabs/Synergy-Starter-Kit/raw/master/Pictures/S5D9%20follow.PNG)

* Click on the Create Custom Dashboard button to launch your [freeboard dashboard](https://renesas.freeboard.io)

![dash1](https://github.com/buglabs/Synergy-Starter-Kit/raw/master/Pictures/dash1.PNG)


## Using Freeboard

Freeboard is a web-based visualization tool used for displaying and interacting with data. Freeboard is open-source and fully-customizable, allowing the user to create rich Internet of Things applications.

### Datasources

Your Renesas Synery Kit comes with software that allows the device to connect to the [dweet messaging platform](https://dweet.io)

The dweet platform is one possible datasource that freeboard can use to display data. Your custom dashboard will already be set up with this datasource, titled Renesas-Dweet (This is a custom instance of dweet supplied by Bug Labs, to Renesas. Further customization is available upon request). 

To add a new datasource, such as a 3rd party API, Click on the ADD button

![Dsource6](https://github.com/buglabs/Synergy-Starter-Kit/raw/master/Pictures/Dsource6.PNG)

Next, choose the datasource you wish to connect. For example, choose the JSON datasource to add a 3rd party web API. In the following example, we choose the Weather datasource

![DSource1](https://github.com/buglabs/Synergy-Starter-Kit/raw/master/Pictures/DSource1.PNG)

Fill out the appropriate details, and click on SAVE

![DSource2](https://github.com/buglabs/Synergy-Starter-Kit/raw/master/Pictures/DSource2.PNG)

Congratulations! You have now added a new datasource. Next we see how to use your new source of data.

### Widgets

The freeboard platform comes with a standard set of widgets to use for visualizing data.  To add a new widget to your dashboard, click on the Add Pane button:

![addpane](https://github.com/buglabs/Synergy-Starter-Kit/raw/master/Pictures/addpane.PNG)

A new pane will be added to the top left of your dashboard. 

Click on the + sign in the header of your new pane.  A selection popup will appear:

![Widget](https://github.com/buglabs/Synergy-Starter-Kit/raw/master/Pictures/Widget.PNG)

Select the widget type you wish to use (in our case we use the gauge).

![Widget2](https://github.com/buglabs/Synergy-Starter-Kit/raw/master/Pictures/Widget2.PNG)

Fill out the information in the widget setup screen, then click SAVE.

![Widget3](https://github.com/buglabs/Synergy-Starter-Kit/raw/master/Pictures/Widget3.PNG)

Congratulations!  You have just added a new widget to your dashboard. 

Next step, keep adding more datasources and widgets, then Share your dashboard.

One last note: Bug Labs provides a set of off-the-shelf widgets to use, however, the user is able to add new widgets and datasource types by adding plugins to the Developer Console

![console](https://github.com/buglabs/Synergy-Starter-Kit/raw/master/Pictures/console.PNG)

Documentation for creating new plugins can be found within the Developer Console.

## Do More

* Try the Cold Chain Demo: https://github.com/buglabs/Synergy-Starter-Kit/blob/master/Cold%20Chain/User%20Guide.md

## Helpful Links
* Freeboard Open Source Repo: (https://github.com/Freeboard/freeboard)
* DweetPro Production ready APIs and UI: (https://dweetpro.io)

![BUG logo gif](https://github.com/buglabs/Synergy-Starter-Kit/raw/master/Pictures/BUG_logo_gif.gif)
