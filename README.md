The project mainly involved 4 subtopics: 
i) Controlling Light using On/Off button (UI) on the smartphone. 
ii) Controlling Light using Voice. 
iii) Controlling Light using LDR. 
iv) Controlling Light using PIR.

We used an Arduino Uno as a microcontroller and connected HC-06 Bluetooth Module to it. 
Using the module we established a connection between the Arduino and the smartphone. 
A 5V 2 Channel Relay Module Shield is used which is connected to the 230V Power supply.

		A. Controlling Light using On/Off button (UI) on the smartphone. On and Off button has the value of a and b respectively. 
    Once the button is pressed it sends the data to the Arduino through the Bluetooth module. The Arduino then sends the signal 
    to the relay (Which acts as a switch) to Control the light.

		B. Controlling Light Using Voice. The app accepts the voice of any language and using Google's API it converts the voice 
    into text and matches the text in the code. We can include alphabets and also Strings.
		
		C. Controlling Light Using LDR. If the Intensity of light in the surrounding becomes less then the light turn on automatically. 
    It doesn't require any human interaction. It can be implemented on the street lights. After dusk, the street lights will 
    automatically turn on and after dawn, it'll turn off itself.

		D. Controlling Light using PIR. When a warm body like a human or animal passes by, the Light will turn on on itself. We have 
    added a delay in our code that turns off the light after 5 sec if there is no motion detected. It can be used near washrooms 
    or any other place where it becomes difficult to find the switches when there is no visibility.

		This Project was implemented using 2 Arduino Uno and a Working Model of the same is made which involves all the subtopics. 
    This Project received 2 Appreciation Certificates and was among the highly discussed projects during the ByteStream Magazine 
    Launch 2018.
