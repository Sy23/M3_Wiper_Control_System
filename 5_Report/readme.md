# REPORT
## Introduction
Working windshield wipers are vital for driver visibility. The vehicle is considered unsafe if the wipers don't work. The front wiper motor and the wiper transmission mechanism (linkage) are installed below the windshield, under the cowl panel cover. Car glass that is exposed to dirt or rainwater will usually be cleaned using a wiper. Usually, the wiper is attached to the front and rear sides. With the wiper, the driver’s view will not be hindered and so they can see clearly towards the front or rear. Wipers do have a very important role in the safety of the riders because wiper performance is closely related to the safety of driving. If it rains a lot and the car doesn’t use wipers, the windshield will be dewy. Visible dew on the glass will block the view of the driver. When the driver’s view is hindered, the risk of an accident is very high. This makes the wipers a very important car enhancement and must be present on all types of vehicles.
A Windshield Wiper is an essential tool in an automobile to have a clear vision by eliminating debris and enabling driving through rain and snow.
This project demonstrates the Wiper Control System in automobiles using an STM32F4xx-Discovery board. The wiper action is demonstrated with the aid of 4 LEDs, Red, Blue, Green, and Orange. To indicate the ignition the Red LED glows on pressing the switch. The Blue, Green, and Orange blink sequentially in a clockwise and counter-clockwise direction to represent wiper action.

## REQUIREMENTS

- STM32 IDE
- STM32F407VG MICROCONTROLLER BOARD
- Xpack Packages 
- OpenOCD 
- QEMU 

## BLOCK DIAGRAM
![Wiper Block Dia](https://user-images.githubusercontent.com/47395151/168476726-e626a70b-7063-419d-8ca9-bd18b2de6c8e.png)
## FLOW CHART
![Wiper FlowChart](https://user-images.githubusercontent.com/47395151/168476818-fbd580f1-6180-4ebb-bbe6-21071f335fce.png)




## HIGH-LEVEL REQUIREMENTS
| ID |Description|Status|
|----|-----------|------|
|HL1|Wiper Action with STM32F407VG|Implemented|
|HL2|Sequential Blink|Implemented|
|HL3|System ON and OFF|Implemented|
## LOW-LEVEL REQUIREMENTS
| ID |Description|Status|
|----|-----------|------|
|LL1|Push Button|Implemented|
|LL2|LED's Working|Implemented|

# 4W & H (WHAT,WHY,WHEN,WHERE,HOW)
- WHAT
A wiper speed control mechanism controls a vehicle wiper's operational speed based on rain conditions. To generate, the control system incorporates a rain sensor that detects rain conditions. The amplitude of an analog signal depends on the detected rain conditions.
- WHY
To keep the windscreen clean enough to give an adequate view at all times. Enables safe and comfortable driving for the driver. 
- WHEN
The windshield wipers remove rain and snow from the windshield, also the debris left behind, while the headlights improve visibility at night.
- WHERE
These are generally present in all heavy motor vehicles but are used regularly at locations that have heavy rainfall and snow.
- HOW
Speed variations can be done in the car wiper system according to the rainfall.

## Car Wiper Components
Car wipers do consist of various components such as the wiper blade, link, switch, motor, and arm.
![Wiper Blade](https://user-images.githubusercontent.com/47395151/168477404-611da4e3-ba5d-47e5-8625-6f0c4d17690e.jpg)


### Wiper Motor

The wiper motor is one part of the wiper system that is useful for moving the wiper automatically. The commonly used wiper motor utilizes a magnet with a reduction gear. There are at least 2 types of wiper motors that can cause magnetic fields, namely the ferrite magnet type which uses permanent magnet ferrite, and the wound rotor type which uses a coil to produce an electromagnet. The wiper motor that is often used recently is the ferrite magnet type because this type of wiper has a relatively small size and has lightweight, so it is very suitable to be attached to any type of car.
![Wiper Motor](https://user-images.githubusercontent.com/47395151/168477407-814ed27b-4e7d-4353-9ca4-4fe999f8a23e.jpg)

### Wiper Link

The wiper link is often referred to as the wiper lever which is useful for changing the rotation motion of the wiper motor into a movement that goes back and forth from the left and right. The front of the car usually uses a wiper system that uses two blades at once and the mechanism used to move the two blades uses a parallel tandem system. When the wiper starts to turn on, the wiper motor will rotate the crank arm and this will make the connecting rods pull and push each other. The wiper link will make the wiper arm work in a semicircle around the pivot shaft. The linking rod or connecting rod which is usually attached to the two wiper arms will make the two blades work simultaneously and work in parallel.
![Wiper Link](https://user-images.githubusercontent.com/47395151/168477406-d521bbe4-2bca-49f0-9d4d-04113c7b8831.jpg)


### Wiper Arm

The wiper arm usually consists of a head that is used to tie the wiper arm to the wiper shaft. The springs will be useful for holding the blade. While the arm piece will be useful for the process of installing the blade and retainer to hold it completely. The wiper blade usually consists of a rubber which is useful for cleaning the surface of the car glass. There is a combination of leaf spring packing with levers and clips to attach the blade to the wiper arm.
![Wiper Arm](https://user-images.githubusercontent.com/47395151/168477405-c7eb8ee2-fcd0-4d7d-bbd8-95dcc37ca7ef.jpg)


## Types of Windshield Wiper Arms

There are many different types of wiper blades available. So, let's get started.

Number 1
Standard (or conventional) Type Wiper Blades
Standard wiper blades are the most common type of windscreen wiper, often referred to as looking like a coat hanger, and are still fitted to the majority of new vehicles, although this is in decline. They are usually attached to the vehicle using a hook shape wiper arm fitting. Sizes range from 10" to 28" and it is not uncommon to have different sizes fitted to the drivers' and passengers' sides of the windscreen. 

Number 2
Spoiler Type Wiper Blades
These types of wiper blades feature a Full Spoiler that runs the length of the blade. This helps to keep the blade closer to the windscreen at higher speeds and is usually designed for the driver's side only. Again they are usually attached to the vehicle using a hook-shaped wiper arm fitting.

Number 3
Retrofit Flat Wiper Blade Upgrade
Flat wiper blades feature a new style and technology and are fast becoming the standard fit on new vehicles. These types of wiper blades do not have a metal 'coat hanger' shaped frame. Instead, they have a tensioned metal strip running within the rubber structure of the wiper blade. This design allows for a flatter aerodynamic shape which reduces wind noise. 

Number 4
Hybrid Wiper Blades
Hybrid wipers combine the aerodynamic shape of a flat blade with the solid construction of a conventional wiper. An articulated plastic frame forms the aerodynamic 'skin' of the wiper blade. This allows for a smoother airflow, which in turn creates an even downforce along the entire length of the blade.

Number 5
Flat Wiper Blades
Flat wiper blades feature a new style and technology and are fast becoming the standard fit on new vehicles. These types of wiper blades do not have a metal 'coat hanger' shaped frame. Instead, they have a tensioned metal strip running within the rubber structure of the wiper blade. This design allows for a flatter aerodynamic shape which reduces wind noise.

Number 6
Specific Fit Wiper Blades
Specific Fit wiper blades are usually Original Equipment replacements and are designed for specific vehicles. Many rear blades are unique in design and need to be replaced with this type of wiper blade. We also offer Twin Packs for the front of some vehicles which need curved wipers, uniquely shaped spoilers, or special fitting adaptors.

Number 7
Rubber Refills

Refills contain the rubber part of the wiper blade only and are designed to replace the existing rubber element. Replacing just the refill is a low-cost alternative to changing the wiper blade, however; changing the complete blade is typically much easier, faster, and will usually produce a better result. Replacing the refill too many times should be avoided, as the wiper blade superstructure will become weaker over time. These refills cannot be used to refill the new type of Flat wiper blade. 
## Operation
When the wiper switch is in the off position, the wiper will not function. When the wiper switch is in low-speed mode, the wiper will work at low speed. Accordingly, when the wiper switch is in high-speed mode, the wiper will work at a fairly high speed.

## Project Scenario

Ignition Key Position at ACC: The Red LED is ON if the user button is pressed and held for 2 secs
Wiper ON: Wiper is OFF: On press of the user input, Blue, Green, and Orange LEDs come ON one at a time with the set frequency, The frequency changes on every alternate keypress, 3 frequency levels with 1, 4, and 8 Hz
Wiper OFF: Wiper is ON: The LED glow pattern stops on the 4th press; the wiper action starts next press onwards as mentioned in step 2
Ignition Key Position at Lock: The Red LED is OFF if the user button is pressed and held for 2 secs

## SWOT ANALYSIS
### STRENGTH
- Low Budget
- User Friendly
### WEAKNESS
- Structural Inertia
- High Transaction Cost
- No Focus on Private Sector

### OPPORTUNITIES 
- Emerging New Markets
- Technological Development

### THREATS
- Highly Regulated Industry
- Ethical Pressure
- Economical Crisis

# SURVEY-COMPARATIVE STUDY
| Mercedes BENZ |      AUDI     |  McLaren P13  |
|---------------|---------------|---------------|
|Magic Vision Control(MVC Technology): Combined operation of spraying and wiping to reduce the water consumption and improve vision| Rain Sensor: Rainfall is sensed and the wiper acts accordingly. It comes with sensitivity control as well. RAINFALL INTENSITY = WIPE FREQUENCY| Uses "Ultrasonic Transducer" to convert electric energy into high-intensity sound waves to eliminate the use of a wiper brush.|

# CONCLUSION
The Wiper Control in automobiles has been studied and implemented using an STM32F407VG Board. 

 



