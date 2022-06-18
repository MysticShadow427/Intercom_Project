# Intercom_Project
An intercom project using Raspberry Pi and Arduino using Serial Communication Protocol

This project is a part of my course which I completed.The main idea of this project is to make an intercom system is to accept or deny the entry of a person from our door by checking the photo clicked by camera on Raspberry Pi and sent to the User through Telegram.
Here Arduino and Raspberry Pi are connected through Serial Communication using USB cable.Here all the major hardware functionalities are handled by Arduino while the all major software functionalities are handled by Raspberry Pi through python code.

Here I have used camera module,telegram bot module to make a telegram bot to  handle telegram commands typed by the User and serial communication module to initiate the commuication.
Hardware components that are used are push button,LCD,LEDs and servo motors(as a similarity to the door) and used their libraries accordingly in the  Arduino Sketch.

The communication between Raspberry Pi and Arduino is done by transfer of strings and UTF-8 encryption.Raspberry Pi decodes commands sent by Arduino whenevr an event happens and then uses it to do some telegram and camera handling.

I have attachted the python code for Raspberry Pi and Arduino Sketch and also the service file of the project to bootstrap directly on your Linux Machine. 
