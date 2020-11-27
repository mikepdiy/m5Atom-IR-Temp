<b>What is this board?</b>


This is what I consider the best thing you can have to use in a HomeAutomation setup as it is small, works with the M5Atom out of the box and it has IR RX and TX , Temp and Humidity. 

<b>How did this board came to life ?</b>

I have recently got into the Apple HomeKit system and I was not that happy with the costs and range of accesorries so I have gotten down the route of HomeBridge and used the amazing system that the people behind this project give to the community . 
Now I needed to reduce the space used by all my messy wires and integrate as many sensors as I could in one small package that can sit in a room.

<b>What does this board offer in terms of sensors : </b>

1. 9 x IR Transmitter LED with 150degree angle of transmission each 
2. 1 x IR Receiver to help in grabbing signals or repeating them
3. 1 x SHT30 Temperature and Humidity Sensor to help in automation setups lilke " IF the Office Temp goes over 28 Celsius then turn AC ON but if it goes under 25 turn AC OFF."

<b>Why to buy this board ? </b>

Well, that would help me and allow me to keep developing boards like this while improving the board I have already made . 
This board in conjuction with some Arduino knowledge will allow you to tailor the way it works to perfectly fit your Home Automation setup.
The software and the pinout of the board is open sourced and you can see all the details you need here in order to play with the software yourself. 
Of course I can not be held responsible if you damage the board while doing this.

<b> Needed software and libraries to work with this board : </b>

IDE : Arduino 1.8.3 ( I assume it will work with others like PlatformIO but I have not tested it so I warrant for Arduino IDE on Windows 10 , MacOS Catalina and linux flavours based on Ubuntu 20.04)

Board BSP : ESP32

Libraries : 

-ESPUI

-AccelStepper

-Adafruit SSD 1306

-Adafvruit GFX

-DNSServer ( possibly included in the ESP32 BSP)


<b> Where to buy the board </b>

Tindie Link Here
