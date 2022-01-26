# Solar-Charge-Controller
Quick and easy getting started application for CONTROLLINO PLCs: Control relays, turn on and off, and monitor voltages.



Hardware Setup

1 	24V and GND to +24 and GND terminals on Controllino (upper right) 
	 
2 	Connect analog input signal to AI0 and GND 
	 
3 	If controlling external device wire to Relay 0 
	 
4 	Turn power on for Controllino and it begins running the application embedded

5 	Plug USB cable into computer and Arduino 

6 	Start LabVIEW application for monitoring operations 


 

Installation of Dependencies 

1 	Install the Arduino Environment 	Version 1.8.18 is the latest 

2 	Install Controllino Library into Arduino IDE 	Library Manager

3 	Copy Paste Board Manager URL into Arduino 	Preferences Tab 
	 
4 	Add Controllino into Boards Manager 	Tools: Board: Board Manager 
	 
5 	For Arduino v 1.6.6 or later, edit debug in	C:\Program Files (x86)\Arduino\arduino_debug.l4j 
	 
6 	Install Arduino Compiler for LabVIEW 	VI Package Manager 

7 	License Arduino Compiler for LabVIEW 	VI Package Manager 

8 	Pull down the LabVIEW Embedded project from Solubit 	Whatever the location is 

9 	Create Executable for Host Application 	Use Project Build Spec 

10 	Compile LabVIEW Target code for Arduino. 	Use the Arduino Compatible Compiler to Compile Target code and deploy to Controllino Target 
	 	
11 	Run Host application 	Launch and you should see voltage levels and relay activity. 





