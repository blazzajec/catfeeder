catfeeder
=========

code for our wireless homework cat feeder


Android - contains our code for the android app that recognizes and connects to our BLE112 chip

Arduino - contains the code for the boarding that actuates the servo based on FRS input. 

BLE112 - contains the code we were building to run our cat feeder. Currently code has the chip show up as "cat feeder" and toggles the led on P0_0 on and off every second. It also sends a reading to Android. We weren't able to get messages received from Android to BLE112. We just weren't able to figure this out, but hope to better understand after looking at how some of our classmates did it. 