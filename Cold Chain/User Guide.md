 ![renesas](https://github.com/buglabs/Synergy-Starter-Kit/raw/master/Pictures/renesas.png)

# User Guide for the Cold Chain Demo dashboard 

https://renesas.freeboard.io/board/cSyXRK

## Purpose:

* Create a demonstration freeboard dashboard that uses the S5D9 Synergy Kit to monitor temperature over time.
* Send an alarm if the temperature rises above a certain threshold.
* Connect History line graph to User-Controllable device output.

![coldchain2](https://github.com/buglabs/Synergy-Starter-Kit/raw/master/Pictures/coldchain2.PNG)

## Using the Dashboard

* First, a trace line forms on a map of San Francisco.
  * This uses simulated data
  * A GPS unit can connect to your S5D9 board via Grove Connector.

* Second, enter the Thing-Name in the upper left box.
  * Click SET
  
* The temperature gauge reads the output from the device.

* The alarm widget outputs a notification at each trigger.

* Finally, the History and Humidity sparklines should activate. 
  * The History sparkline is connected to the accelerometer for demonstration purposes.
  
### Doing more

* You can customize this dashboard by "Cloning" the board. Click on the Clone button.
  * You may be instructed to sign in.
  * Instructions for adding new datasources and new widgets is here:
  https://github.com/buglabs/Synergy-Starter-Kit/blob/master/README.md
  
* After cloning, click on the wrench in the Alarm widget to set new alerts.
  * You can also set an email address or SMS to receive alerts.
  
  ![Notification widget1](https://github.com/buglabs/Synergy-Starter-Kit/raw/master/Pictures/Notification%20widget1.PNG)
  
 * Customize as needed, then share your new URL!
 
 ![BUG_logo_gif](https://github.com/buglabs/Synergy-Starter-Kit/raw/master/Pictures/BUG_logo_gif.gif)
  
