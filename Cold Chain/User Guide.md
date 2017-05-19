 ![renesas](https://github.com/buglabs/Synergy-Starter-Kit/raw/master/Pictures/renesas.png)

# User Guide for the Cold Chain Demo dashboard 

## Purpose:

* Create a demonstration freeboard dashboard that uses the S5D9 Synergy Kit to monitor temperature over time.
* Send an alarm if the temperature rises above a certain threshold.
* Connect History line graph to User-Controllable device output.

![coldchain3](https://github.com/buglabs/Synergy-Starter-Kit/raw/master/Pictures/coldchain3.PNG)

## Using the Dashboard

Click on the following link:

https://renesas.freeboard.io/board/cSyXRK

* First, a trace line forms on a map of San Francisco.
  * This uses simulated data.
  * A GPS unit can connect to your S5D9 board via Grove Connector.

* Second, enter the Thing-Name of your S5D9 board in the upper left box.
  * Click SET.
  * [Instructions for finding your thing name can be found here.](https://github.com/buglabs/Synergy-Starter-Kit/blob/master/README.md)
  
* The Temperature gauge reads the output from the device.
  * This will set the Alarm widget to one degree Fahrenheit below the first temperature reading from your board.
  * The Alarm Set point will show in the Dynamic Alert Value widget.

* The Alarms widget outputs a notification at each trigger.
  * The alarm widget will start to show notifications.

* Finally, the History and Humidity sparklines should activate. 
  * The History sparkline is connected to the accelerometer for demonstration purposes.
  
### Doing more

* You can customize this dashboard by "Cloning" the board. Click on the Clone button.
  * [You may be instructed to login.](https://renesas.freeboard.io/login)
  * Instructions for adding new datasources and new widgets are here:
  https://github.com/buglabs/Synergy-Starter-Kit/blob/master/README.md
  
* After cloning, click on the wrench in the Alarm widget to set new alerts.
  * You can also set an email address or SMS number to receive alerts.
  
![Notification widget1](https://github.com/buglabs/Synergy-Starter-Kit/raw/master/Pictures/Notification%20widget1.PNG)
  
* Customize as needed, then share your new URL!
 
### Notes

Need an account? [Sign up here!](https://renesas.freeboard.io/signup)
 
 ![BUG_logo_gif](https://github.com/buglabs/Synergy-Starter-Kit/raw/master/Pictures/BUG_logo_gif.gif)
  
