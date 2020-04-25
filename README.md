# AccelerometerSensor
Accelerometer Sensor - Android Mobile Sensing Application - API 28 must be used to run this Android Accelerometer Sensor Mobile Sensing Application

## Group Team Members
- Parsa Ahmadi Nasab Emran
- Abdullah Jandali

## List of Features That Have Been Implemented In This Android Accelerometer Sensor Mobile Sensing Application
- a reset button that would change the background color to white
- devie rotation to the left to reject the call - the background color will be changed to red and the "You have rejected the call." message will be displayed
- device rotation to the right to answer the call - the background color will be changed to green and the "You have answered the call." message will be displayed
- swipe to the left to reject the call - the background color will be changed to red and the "You have rejected the call." mwssage will be displayed
- swipe to the right to answer the call - the background will be changed to green and the "You have answered the call." message will be displayed
- swuipe to the top - the background color will be changed to white and the "You have swiped upwards." message will be displayed
- swipe to the bottom - the background color will be changed to white and the "You have swiped downwards." message will be displayed
- x value is displayed in its own text view
- y value is displayed in its own text view
- z value is displayed in its own text view
- x, y, and z data values are plotted in real time using MPAndroidChartLibrary

## Insights and Findings

**Plotting of Accelerometer Sensor Data Values**
- At first, we were thinking about plotting of Accelerometer Sensor Data Values by exporting it to a csv file and then visualizing it from csv format to chart using Python. And then we ran into the MPAndroidChart Library which allowed us to plot the Accelerometer Sensor data values in real time as the sensor was reading them. So, we have decided to be using MPAndroidChart Library to plot the Accelerometer Sensor data in real time and not have to export them to a csv file and the visualizing it from csv format to chart using Python.

**Using a Gyroscope Sensor For Rotation of The Device**
- At first, we were thinking about using the Gyroscope Sensor for rotation of the device. But when we tried rotating the devuce using the Gyroscope Sensor, we ran into the problem about its x, y, and z values being all zeros regardless of if the device was rotated to the right or to the left. Then, we have decided to include the rotation of the device in its Accelerometer Sensor since we have used its x values to decide whether the background color should change to either green or red.

**Keeping It Clean And User Friendly**

## Goal
The goal of this Android Accelerometer Sensor Mobile Application is to allow users to control their incoming phone calls. This application allows them to either rotate their phones to the left to reject the call or rotate their phones to the right to answer the call. This application also allows the users to either swipe to the left to reject the call or swipe to the right to answer the call. The users can also press/tap the Reset button to change the background color to white again. This application also displays the x, y, and z data values for the users to see. This application also plots the x, y, and z data values in real time for the users to see. The application also allows the users to swipe upwards or downwards to change the background color to white again.

This application will also display a toast message: "You have rejected the call." when the device is being rotated to the left. This application will also display a toast message: "You have answered the call." when the device is being rotated to the right. This application will also display a toast message: "You have rejected the call." when swiping to the left. This application will display a toast message: "You have answered the call." when swiping to the right. This application will also display a toast message: "You have swiped upwards." when swiping to the top. This application will also display a toast message "You have swiped downwards." when swiping downwards.

## Application/Scenario
Its for people who need help with controlling of their incoming phone calls. This application allows them to either rotate their phones to the left to reject the call or rotate their phones to the right to answer the calls. This application also allows them to either swipe to the left to reject the call or swipe to the right to answer the call. This application also allows the users to change the background color to white by pressing/tapping the reset button, swipe to the top, or swipe to the bottom. This application displays the x, y, and z data values to them. This applicatiom displays the plotting of x, y, and z data values in real time to them.
