**Chicken Incubator**

Published on 2021.07.23

Author :-

 Rathees Koneswaran, Community maker at Dream Space Academy.
 Find me [here]()

Acknowledgment :-

 Aravith Panch , Co-founder and Director of Innovation, DreamSpace Academy , Batticaloa , Sri Lanka.

 Kishoh Navaretnarjah , Co-founder and Director, DreamSpace Academy

**Abstract**

Chicken incubator is a device which is used for keeping eggs for hatching them.

This project is to create a chicken incubator with electronic devices and some other parts. We can make a chicken incubator with only some basic knowledge in electronics and electricity.

**Introduction**

An incubator is a device simulating avian incubation by keeping eggs warm at a particular temperature range and in the correct humidity with a turning mechanism to hatch them. The common names of the incubator in other terms include breeding / hatching machines or hatchers, setters, and egg breeding / equipment.

In the current world, an increase in population needs a massive food supply as fast. Chicken is the most desired food by people and producing them in large amounts is a requirement for farmers. Introducing a machine which can hatch huge amounts of eggs at the same time is a great solution for this need. 

In this project we are going to make a chicken incubator. This machine works in electricity and there is no need for a hen to hatch the eggs. So, we can hatch a big number of eggs in this machine at the same time and we can increase this number by expanding the size of the box.

**Problem Statement**

Using hens for hatching eggs to produce chicken is not possible for a big requirement in the market.

**Things need to make**

* 1x thermocole box 20 liter
* 1x Bulb holder
* 1x 100 watt halogen bulb
* 1x 12v Digital Thermostat
* 1x 12v Fan
* 1x 12v Adaptor
* 3x Zip Ties
* 1x Disposable plastic bowls
* 1x 3d printer

**Block Diagram**

![Getting started](source\images\block-diagam.png)

**Circuit Diagram**

![Getting started](source\images\circuit-diagram.png)

**Print a plastic case for Thermostat**

If you like to cover your thermostat, you can download the stl format file [here](source\stl-files). And print it in your 3D printer. Top side of your case will be like this image.

![Getting Started](source\images\top-of-case.jpg)

**Making incubator**

![Getting started](source\images\inside-of-incubator.jpg)

![Getting started](source\images\out-side-of-incubator.jpg)

You have to design a circuit like above and then take the thermocole box to fix components. You have to fix the light and fan inside of the thermocol box and fix the thermostat outside. After that make some holes in the walls of the thermocol box to manage air circulation in the box. Now your incubator is ready to use. Finally, set the temperature into 37.5 oC. set p0 as H and p1 as 0.5.( you can change if your need )

**How to use Thermostat**

DESCRIPTION:

The W1209 is an incredibly low cost yet highly functional thermostat controller. With this module

you can intelligently control power to most types of electrical device based on the temperature

sensed by the included high accuracy NTC temperature sensor. Although this module has an

embedded microcontroller no programming knowledge is required. 3 tactile switches allow for

configuring various parameters including on & off trigger temperatures. The on board relay can

switch up to a maximum of 240V AC at 5A or 14V DC at 10A. The current temperature is displayed in degrees Centigrade via its 3 digit seven segment display and the current relay state by an on board LED. 

**SPECIFICATION:**

* Temperature Control Range: -50 ~ 110 C
* Resolution at -9.9 to 99.9: 0.1 C
* Resolution at all other temperatures: 1 C
* Measurement Accuracy: 0.1 C
* Control Accuracy: 0.1 C
* Refresh Rate: 0.5 Seconds
* Input Power (DC): 12V
* Measuring Inputs: NTC (10K 0.5%)
* Waterproof Sensor: 0.5M
* Output: 1 Channel Relay Output, Capacity: 10A
* Power Consumption
* Static Current: &lt;=35mA
* Current: &lt;=65mA

**Environmental Requirements:**

* Temperature: -10 ~ 60 C
* Humidity: 20-85%

**Dimensions:**

* 48mm x 40mm x 14mm

**Settings Chart:**

* Long press the “SET” button to activate the menu.
* Code Description Range Default Value
* P0 Heat C/H C
* P1 Backlash Set 0.1-15 2
* P2 Upper Limit 110 110
* P3 Lower Limit -50 -50
* P4 Correction -7.0 ~ 7.0 0
* P5 Delay Start Time 0-10 mins 0
* P6 High Temperature Alarm 0-110 OFF
* Long pressing +- will reset all values to their default

**Displaying the current temperature:**

* The thermostat will display the current temperature in oC by default. When in any other mode making no input for approximately 5 seconds will cause the thermostat to return to this default display.

**Setting the trigger temperature:**

* To set the trigger temperature press the button marked 'SET'. The seven segment display will flash.You can now set a trigger temperature (in oC) using the '+' and '-' buttons in 0.1 degree increments. If no buttons are pressed for approximately 2 seconds the trigger temperature will be stored and the display will return back to the current temperature.

**Setting the parameters:**

* To set any parameter, first long press the 'SET' button for at least 5 seconds. The seven segment display should now display 'P0'. This represents parameter P0. Pressing the '+' or '-' buttons will cycle through the various parameters (P0 to P6). Pressing the 'SET' button whilst any of these parameters are displayed will allow you to change the value for that parameter using the '+' and '-' buttons. When finished setting a parameter press the set button to exit that option. If no buttons are pressed for approximately 5 seconds the thermostat will exit the parameter options and will return back to the default temperature display.

**Setting the cooling or heating parameter P0:**

* The parameter P0 has two settings, C and H. When set to C (default) the relay will energise when the temperature is reached. Use this setting if connecting to an air-conditioning system. When set to H the relay will de-energise when the temperature is reached. Use this setting if controlling a heating device.

**Setting the hysteresis parameter P1:**

* This sets how much change in temperature must occur before the relay will change state. For example if set to the default 2oC and the trigger temperature has been set to 25oC, it will not deenergise until the temperature falls back below below 23oC. Setting this hysteresis helps stop the thermostat from continually triggering when the temperature drifts around the trip temperature.
