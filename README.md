# IoTry

Project to learn and gain more firmware experience hands-on. I will be using the B-L475E-IOT01A Discovery board as the base unit. This will have two sets of folders, one to deal with testing concepts and what systems work (HAL Folder) and one with my actual code developed without the use of libraries.  
  
The overall objective is to communicate with the different sensors on the board using I2C communication to read the register values from the accelerometer and gyroscope. Then I will create a UART driver to display their information on a serial terminal such as PuTTY.  
  
Once these steps are complete, I will attempt to learn more about WIFI operation and host a web server using the WIFI module to display the sensor data on a website. If theres room in the code and the pinout of the device, I will try to implement an RTOS to handle all the different systems operating at once.  
  
I will also create a folder with the most relevant documents used in developing this system. 

#### Additional Background
The L4 line from STM32 does not have a standard peripheral library, with only HAl and the LL libraries available for usage. Since I'm not too familiar I will be working with the HAL libraries. 
Why do I continue with this and HAL? I already have the dev kit so I thought I might as well continue working and developing from it. At least for now, until I find some alternatives, which will be coming soon-ish hopefully. Finding a replacement WIFI module will be a bit more annoying. 

## Why

I have the discovery board on hand and it comes with several sensors already installed on it, and already implemented using I2C lines. This is a 2 for 1 special where not only do I get experience with more sensor peripherals, but I'll also work on figuring out how to develop an I2C driver to read this. Added in with the UART, that's two communication protocols and experience developing drivers (in bare metal).  
  
Lastly, since this discovery board has WIFI and Bluetooth connectivity, there is additional potential to learn more systems, especially that deal with IoT. Paired with the  introduction of an RTOS, this becomes a very well rounded project with lots of learning opportunities.
