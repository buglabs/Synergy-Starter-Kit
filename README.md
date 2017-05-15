![Renesas](https://github.com/buglabs/Synergy-Starter-Kit/raw/master/Pictures/renesas.png)

# Renesas IoT Sandbox  S5D9 Synergy Starter Kit 
## Data Monitoring, powered by Bug Labs, Inc. 

Repository for the Renesas IoT Sandbox, Synergy Starter Kit, Data Monitoring powered by Bug Labs Software, Code, and Guide

**Table of Contents** 
- [Getting Started](#getting-started)
- [Using Freeboard](#using-freeboard)
- [Do More](#do-more)
- [Helpful Links](#helpful-links)

## Getting Started

### Step 1 

* Take the board out of the box and connect<sup>[1](#myfootnote1)</sup> the USB port on the board to a USB port on your laptop.  This will power up the board and the board will enumerate as a USB drive on your laptop.  

* Now connect<sup>[1](#myfootnote1)</sup> the Ethernet port on the board to an Ethernet port on a network router which is internet enabled. 

![S5D9 layout](https://github.com/buglabs/Synergy-Starter-Kit/blob/master/Pictures/S5D9%20layout.PNG)

### Step 2 

* Click on the USB drive which represents your board.  
* Find the “ThingName.txt” file and open it.  The file will contain the Thing Name for your board.  
* Now open a web browser and go to www.renesas.com/iotsandbox/S5D9/getstarted.  
* Enter your board’s Thing Name into the field marked “Enter Thing Name here…” and press the “Try it now!” button.  

![thingnamebox](https://github.com/buglabs/Synergy-Starter-Kit/raw/master/Pictures/thingnamebox.PNG)

At this point, you should see sensor data from your board streaming to the dashboard at an update rate of approximately once per second.  You can shake the board to watch the accelerometer readings change or snap your fingers and watch the sound level change.  You can also click on the button in the browser marked “RED LED” and watch it turn on the LED on your board.  

![dash2](https://github.com/buglabs/Synergy-Starter-Kit/raw/master/Pictures/dash2.PNG)

Congratulations you’ve just successfully setup your board for data monitoring!

## Using Freeboard

[Freeboard](https://freeboard.io) is a web-based visualization tool used for displaying and interacting with data. [Freeboard](https://freeboard.io) is open-source and fully-customizable, allowing the user to create rich Internet of Things applications.

### Datasources

Your Renesas Synery Kit comes with software that allows the device to connect to the [dweet messaging platform](https://dweet.io).

The dweet platform is one possible datasource that freeboard can use to display data. Your custom dashboard will already be set up with this datasource, titled Renesas-Dweet (This is a custom instance of dweet supplied by Bug Labs, to Renesas. Further customization is available upon request). 

To add a new datasource, such as a 3rd party API, Click on the ADD button.

![Dsource6](https://github.com/buglabs/Synergy-Starter-Kit/raw/master/Pictures/Dsource6.PNG)

Next, choose the datasource you wish to connect. For example, choose the JSON datasource to add a 3rd party web API. In the following example, we choose the Weather datasource.

![DSource1](https://github.com/buglabs/Synergy-Starter-Kit/raw/master/Pictures/DSource1.PNG)

Fill out the appropriate details, and click on SAVE.

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

One last note: Bug Labs provides a set of off-the-shelf widgets to use, however, the user is able to add new widgets and datasource types by adding plugins to the Developer Console.

![console](https://github.com/buglabs/Synergy-Starter-Kit/raw/master/Pictures/console.PNG)

Documentation for creating new plugins can be found within the Developer Console.

## Do More

* Try the Cold Chain Demo: https://github.com/buglabs/Synergy-Starter-Kit/blob/master/Cold%20Chain/User%20Guide.md
* View the Data Monitoring API documentation: https://renesas.dweet.io/play/
* Using the S3A7 kit: https://github.com/buglabs/Synergy-Starter-Kit/blob/master/S3A7/readme.md

## Helpful Links

* Support for the S5D9 can be found here: (http://renesasrulz.com/iot/)
* Freeboard Open Source Repo: (https://github.com/Freeboard/freeboard)
* DweetPro Production ready APIs and UI: (https://dweetpro.io)
* [Data Monitoring developer area](https://renesas.dweet.io/) 

## Notes

<a name="myfootnote1">1</a>: USB and Ethernet cables are not included.


![BUG logo gif](https://github.com/buglabs/Synergy-Starter-Kit/raw/master/Pictures/BUG_logo_gif.gif)
