# cjmcu-kzq-sample
This is sample of using CJMCU-KZQ board to control NeoPixel LEDs. I found joy with this cheap board, hope this sample helps you a little bit<br>
All that we need is the USB to TTL UART CP2102, Arduino IDE, and NeoPixel codes ^_^ <br>
#### USB CP2102 adapter
Find download and install the driver for the CP2102 at https://www.silabs.com/developers/usb-to-uart-bridge-vcp-drivers

#### Arduino Settings

On the Arduino IDE set following:
<ol>
<li> Board: Arduino Pro or Pro Mini </li>
<li> Processor: ATmega328P (5V, 16MHz) </li>
<li> Port: /dev/cu.SLAB_USBtoUART (on MacOS, maybe different on your OS) </li>
<li> Programmer: USBasp </li>
</ol>

#### Connection
For connections between CP2101, CJMCU-KZQ and the NeoPixel LEDs, you can refer to mine below:
![alt text](images/CJMCU-KZQ.jpg "Title")

You can refer to https://github.com/dieter-l-git/CJMCU-KZQ-Documentation/blob/master/schematic.pdf for more information<br>
Many thanks to [@dieter-l-git](https://github.com/dieter-l-git/CJMCU-KZQ-Documentation) who did a great work on the schematic of CJMCU-KZQ


#### Demo
https://www.youtube.com/watch?v=ZqvJpk6eiAc

Thank you!