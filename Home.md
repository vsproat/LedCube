Welcome to the LED-Cube wiki!
![Cube info](E:\starkstatecollegeclubs\SoftwareDevelopment\20190219Cube)

8x8x8 Cube Information
Four key functions and 3 music Key functions
 Parts
#	8x8x8 Cube Information
1. PCB Board: 15x15 cm (The dimension is ~1.5 mm larger on one side)
1. 	LEDs	Blue 512 	
1. amplifier audio 3W speaker   
1. Potentiometer 33	Volume adjust	8	K1,K2,K3,K4, S1,S2,S3,?
1. TF memory card to play music, U disk slot		1	
1. 3D8 on the machine mode (control animation)			
1. Through the audio line input and output music			
1. 3D8 on the machine music mode* Infrared remote control			
1. Night, daytime control Switch			
1. PWM breathing light Switch			
11. Switch on the mainboard automatic detection mode			
1. Optocoupler Input 5ma, Output 60 ma, 100 mW	3	U20, U21, U22
1. Microcontroller	STC12C5A60S2	1	
1. 74HC245D buffer driver (cascade connection) 6ma drive	2	
1. 74HC133 D		1	
1. 74HC595N		9	
1. EL 817 C716 PHOTOTRANSISTOR PHOTOCOUPLER 3	
1. High-speed scanning chip and serial control cascade chip		
1. Uses professional MP3 music chip 
1. Use professional power amplifier chip 8002B		
1. Push button or Switch key functions Four	
1. LED	Power indicator, 		
1. Resistors	551  550 OHM	16	
1. Capacitor	220 UF,10 V VT	4	C2,  C6, C13, C18
1. Capacitor	Small surface mount	8	C10, C11,C12, 14,15,16?
1. Socket pins for LEDs base 1/10 inch spacing 80	
1. Socket 	Microcontroller 40 pins	1	
1. USB Programmer module USB – TTL, USB – STC- ISP		
1. Screws		16	
1. Stand off	9 mm	4	
1. Stand off	15 mm	4	
1. String			
1. Power jack	3 pins		
1. TC4953 PDA00707 1S Dual P-Channel 30-V (D-S) MOSFET 5A high-current MOS tube driver chip (to solve the uneven brightness) may only be rated at 3A	4	U1, U2, U3, U5
1. Jack 3.5 mm	 5 pins	2	P2, P3
1. Switch Slide 	5 pins	1	S2
1. Switch push	8 pins	1	S1
1. Crystal 	22.1184 Mhz	1	Y1 under CPU socket
1. IR Sensor CHO 1838,  VS1838-Infrared-Receiver-datasheet	1 To the left of K4
1. Resistors	10K ohms	5	
1. Resistors	0 ohm	2	
1. Resistors	22K ohms	2	
1. music chip AB1727CHCC3T.1-82 https://chipmusic.org/  1 U19, U15
1. 8 pin chip 1	
1. 13-input NAND gate
1. LED Red	7 in 4 corners LED1, LED2, LED3, LED4,LED 5 near center of board 
1. Photoresistor automatic dimming function 1 RG1, next to IR sensor
1. Resistors	ohms package red 30P	3	
1. connector	4 pin 90 degree	1 J1
1. Resistor	Purple 	3	
1. Resistor	33K	2	
1. Resistor	1K ohms	3	
1. Resistor	4R7 , ?4.7K?	2	
1. Resistor	104, ?10K ohms	3	
1. Resistor	513, 51K ohms	2	
1. Resistor	Red 100P	3
***
## # •	Features:
* Voltage: 5V DC
* Current: 1A-2A(2A effect is better.)
* Size:	PCB Board:15 x 15cm	Base Board:17.2 x 15.2cm
* Power supply:mobile phone chargers,computers,charging
* PCB using RF - 4A grade board, LED the spacing between 20 mm
* Built-in 3W amplifier + 3W high-quality speaker
* Built-in MP3 music, the volume can be adjusted
* built-in MP3 music function,accompanied by music rhythm to jump, show a brilliant effect
* Built-in music can be controlled by a button on the next song
* Built-in 42 kinds of off-line stunning animation (plug in the electricity can run animation)
* Built-in 14 kinds of offline dynamic audio animation (dance with music)
* Can be inserted TF memory card to play music
* Can be inserted U disk to play music
* Through the audio line input and output music
* 3D8 on the machine mode (control animation)
* 3D8 on the machine music mode* Infrared remote control function.(long distance control)
* Night, daytime control mode
* PWM breathing light mode
* Switch on the mainboard automatic detection mode
* Photoresistor automatic dimming function (need to expand by yourself)

***
###  Circuit design:
* Chips STC12C5A60S2 + 74HC245 + 74HC138 + 74HC595N
* •	1. Integrated STC12C5A60S2 high-speed 1T microcontroller
* •	2. 74HC245 buffer driver (cascade connection)
* •	3. 5A high-current MOS tube driver chip (to solve the uneven brightness)
* •	4. High-speed scanning chip and serial control cascade chip
* •	5. Use professional MP3 music chip6. Use professional power amplifier chip 8002B
***
### Four key functions:
* K1 key: Enter the mode selection, day, night mode control
* K2 key: Enter the 3D8 PC mode (press the K1 key to be effective after power on)
* K3 key: Enter 42 kinds of offline animation mode (press the K1 key to be effective after power on)
* K4 key: Enter 14 kinds of off-line audio mode (press the K1 key to be effective after power on) 
### Three music keys features: 
* S1 key: Enter the music playback / stop control
* S2 key: Enter the previous song / volume decrease control
* S3 key: Enter the next song / volume increase control
### Two ways to modify the pattern:
* 1. Modify the program (difficult, you need to understand programming)
* 2. PC computer software direct manipulation of the light cubic

***
### Resources:
https://www.instructables.com/id/Led-Cube-8x8x8/
http://forum.hobbycomponents.com/viewtopic.php?t=1744
https://github.com/enjrolas/L3D-Hardware/blob/master/1x1x1%20cube/L3D_Necklace_Rev1%20BOM.txt

* Pictures, Schematic, Code: https://github.com/VectStudio/LED_CUBE
* Code:  https://github.com/pertbanking/led-cube
* Development and Spatial design user program:  https://github.com/tomazas/ledcube8x8x8