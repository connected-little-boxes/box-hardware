## LED Ring with Button
![Some connected little boxes](images/ringbox-proj.jpg)

This is a little box that contains a pixel ring and a button in the middle.

You can set colours, patterns or changing displays on the led ring and read an input using the button. You'll need:

1. A Wemos D1 Mini
2. A 50mm diameter 12 pixel ring
3. A 23mm diameter arcade push button 
4. Two 6mm M3 bolts to hold the Wemos in place
5. A micro-USB cable
6. A usb power supply (a phone charger works great)

The software is configured to use a 12 pixel display. However, you will need to enable the button on the device:

```
pushbuttonfitted=yes
```
You can use the buttontest command to check if your button is connected properly:
```
buttontest
Processing: buttontest Button Sensor test
Press the ESC key to end the test
    pressed: 1
    pressed: 2
    pressed: 3
Button test ended
```
You can find out what commands you can use with the buttons and lights here: https://github.com/connected-little-boxes/box-code/blob/main/doc/Connected%20Little%20Box%20Reference.pdf
