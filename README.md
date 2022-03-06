# 2021 fall K-SW project : team 'BEEP'
experimental field 및 sensor board, Location decision algorithm 

## Research problem statement & Significance
In existing researches, fire is detected using image data. 
but in this case, the amount of data to be processed increases and the fire cannot be prevented in the early stages due to time.
This research detects fires with small data and reduces the amount of data that can finally be processed.


## Environment settings
####  a. experimental field : 
+ consists of a square with side lengths of 48 inches, a grid of 4 by 4 lines on the field.

<img src="https://user-images.githubusercontent.com/68414594/144638993-e1e913e3-b151-4eb4-8126-1b5cd7c4591d.jpg" width="400" height="400"/>

    
####  b. sensor board :
+ equipped in each corner
+ connected to the Arduino to detect fire attached to sensor towers
+ using Arduino MKR WAN 1310 supported by LoRa 
+ Developing Environment : Windows / Arduino IDE 1.8.16 with LoRa Library

![image](https://user-images.githubusercontent.com/68414594/156910571-fb0560d8-b490-432a-a6c7-f2979ba6390d.png)

+ Sensor board's Arduino circuit <br><br>
![image](https://user-images.githubusercontent.com/68414594/156910635-822c2ff4-44d2-4811-8357-765675178903.png)




####  c. concentrator : 
+ Arduino MKR WAN 1310 supported by LoRa
+ Raspberry Pi 4 Model B
+ Developing Environment : Windows / Arduino IDE 1.8.16
