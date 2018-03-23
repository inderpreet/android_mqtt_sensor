# Simple Android App for reading sensor data and sending it over via MQTT

This is a work in progress for an Android Application that will read sensor data from an ambient sensor
and then send it over cellular network to an MQTT broker. Once this is working, it can be merged with
bluetooth sensors to read a number of variables and then send them to the cloud for processing.

The original MQTT app is by [Thumar](https://github.com/Thumar/MQTT)

## Progress

- The basic MQTT functionality works thanks to the original author.
- Ambient Light Sensor value is read and is updated to a textView in the Main Activity. [Link](https://www.youtube.com/watch?v=dfTeS41BbbI)
- Got a thread working separately with a delay using thread.sleep()
- Got the thread to update the sensor data to a View Component after delays. Updating the delay to 5 seconds.
- Got the App sending the sensor data when a toggle button is set. It also stops sending data if the app goes into the background.

## License

GPLv2. No support, Copy at your own risk, You cannot sell it and You cannot cut out the original author's name.