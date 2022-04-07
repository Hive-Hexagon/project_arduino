# Arduino Project Workshop
*pedago: cchen@student.hive.fi*

The goal of this Workshop is to introduce you to a powerful idea. The idea that a computer is far more than the idle machines on our desks. We want to convince you that computers are universal machines that can be anything you imagine. They can exist in many shapes and forms, with possible functions limited only by your dreams.

They are the intelligence silently running the world around us. They are there in your pockets, in the air-conditioners on campus, and in your cars monitoring and controlling its many internal functions. Getting food to your table, and powering your lights involves nothing short of a series of minor technological miracles in planning, transport and storage. The management of logistical networks, communication systems, electrical grids, and agrigultural production equipment all involve sophisticated computational equipment. Computers control the [rovers](https://en.wikipedia.org/wiki/Perseverance_(rover)) currently exploring the surface of Mars, the deep-space [observatories](https://en.wikipedia.org/wiki/James_Webb_Space_Telescope) unveiling mysteries of the universe, and many other scientific instruments expanding the frontiers of knowledge. It's not that everything is carrying around armies of laptops. Instead, most computers in the world are small invisible "parts" embedded into the equipment we use. These are [Embedded Systems](https://en.wikipedia.org/wiki/Embedded_system). Perhaps one day, they may even give rise to synthetic creatures and [artificial life-forms](https://books.google.fi/books/about/The_Lifecycle_of_Software_Objects.html?id=8kYERQAACAAJ&redir_esc=y) that redefine what it means to be alive.

We have designed the Arduino Piscine as an introduction to embedded systems, with projects that gradually increase in complexity. There will not be any strict norm requirements for the projects either, but you will need to show your code to your evaluator. You are instructed to record videos of your projects working in action, which will then be used for evaluations at the end of the Piscine. This is because you will need to reuse the hard-ware components for each project.

We hope that this will inspire your inner engineer, and get you to dream of even greater possibilities for what you can do. We look forward to seeing what you make!

The projects below are split into [foundational](#foundation-projects), [intermediate](#intermediate-projects) and [advanced](#advanced-projects) sections. The Foundational projects will introduce you to the basics of working with an Arduino, designing schematics, and controlling inputs and outputs. They will come with the list of hardware components you need for each project, you may only use the listed components. The intermediate projects will expand on what you learned, developing more work with analog sensors and motors. Once you reached the advanced section, you will have the option to create anything you want. If you don't know what to make, you can continue to follow the advanced projects. The advanced projects are really just to guide your ideas, so have looser requirements.

## Safety
As with any hobby or craft, you are responsible to take care of yourself and those around you. Especially when working with electronics, take extra-precaution and please use common sense. You will be working with basic hand tools, battery powered electrical devices, and cutters. It can be easy to damage Arduino boards if you are not careful, so if you have any uncertainties or questions, it's best to inform yourself before trying anything you're unsure about.

At **NO POINT** will you be required to use soldering irons or work with the mains current on campus. Nor should you... Soldering irons are a fire hazard on campus, and contacting the mains current will kill you. You've been warned. Please don't be stupid, don't do anything dangerous.

[![](https://media.giphy.com/media/LpkLWXTp0v0qy70xPp/giphy.gif)](https://youtu.be/mvDi_O8fgCY?t=295)

## Foundation Projects
Many of these projects are taken from the book [Arduino Workshop: A hands-on introduction with 65 projects](https://books.google.fi/books/about/Arduino_Workshop.html?id=PUm8tCA6L-kC&printsec=frontcover&source=kp_read_button&hl=en&redir_esc=y#v=onepage&q&f=false) by John Boxall. It's a great book with many fun projects. We have compressed some of the foundational projects in this "Piscine" to get you started. We recommend you check out this book, it will help you figure out how to approach these exercises. The google preview should be enough to give you what you need.

With these projects, you will learn:
* Concepts of good project design
* Basic properties of electricity
* About the resistor, light-emitting diode (LED), breadboard, transistor, rectifier diode, relay, and capacitor.
* How to read schematics, and the language of electronic circuits.
* How to use digital input and outputs to create light effects
* The difference between analog and digital

Now go forth budding engineers, let there be photons.

![](https://media.giphy.com/media/31nxeV6V6ecgw/giphy.gif)

---
### Exercise 01
| Ex 01 | Hello World |
| ------| ----------- |
| Description | The Hello World of an Arduino! Figure out how to blink the little L LED light on the Arduino board. |
| Hardware | 1 Arduino & USB cable |

---
### Exercise 02
| Ex 02 | Hello World v2 |
| ----- | -------------- |
| Description | Level up the Hello World. Light up a single external LED |
| Hardware: | <ul><li>1 Breadboard</li><li>1 LED</li><li>1 220 Ω resistor</li><li>3 wires</li><li>1 Arduino & USB cable</li></ul> |

---
### Exercise 03
| Ex 03 | Blinking LED Wave |
| ----- | ----------------- |
| Description | Let’s light an LED Wave! You will need to light up 5 LEDs in a row, in a wave light pattern. Like the TV show car KITT from knight rider. |
| Hardware | <ul><li>5 LEDs</li><li>5 560 Ω resistors</li><li>1 breadboard</li><li>Bunch of connecting wires</li><li>1 Arduino & USB cable</li></ul> |

---
### Exercise 04
| Ex 04 | Demonstrate a Pulse-width Modulation (PWM) |
| ----- | ------------------------------------------ |
| Description | Create a “breathing effect” on light 3 from the project above. |
| Hardware | Same as Ex 03 |

---
### Exercise 05
| Ex 05 | Implement a digital input |
| ----- | ------------------------- |
| Description | Implement a button that turns on an LED for half a second when pressed. At this point it would be a **really good idea** to start looking into schematic diagrams. |
| Hardware | <ul><li>1 push button</li><li>1 LED</li><li>1 560 Ω resistor</li><li>1 10 kΩ resistor</li><li>1 100 nF capacitor</li><li>Various connecting wires</li><li>1 breadboard</li></ul> |

---
### Exercise 06
| Ex 06 | Traffic lights |
| ----- | -------------- |
| Description | Pretend there is a single lane bridge. You must implement 2 sets of traffic lights at each end of this bridge. The lights will allow traffic to flow only in one direction at a time. When sensors at either end of a bridge detect a car waiting at a red light, the lights will change to allow traffic to flow in the opposite direction. |
| Hardware | <ul><li>2 red LEDs (LED1 and LED2)</li><li>2 yellow LEDs (LED3 and LED4)</li><li>2 green LEDs (LED5 and LED6)</li><li>6 60 Ω resistors (R1 to R6)</li><li>2 10 kΩ resistor (R7 and R8)</li><li>2 100 nF capacitors (C1 and C2)</li><li>2 push buttons (S1 and S2)</li><li>1 medium-sized breadboard</li><li>1 Arduino and USB cable</li><li>Various connecting wires</li></ul> |

---
### Exercise 07
| Ex 07 | Single-Cell Battery Tester |
| ----- | -------------------------- |
| Description | Measure the voltage of a battery, and express the battery condition visually with LEDs |
| Hardware | <ul><li>3 560 Ω resistors</li><li>1 2.2 kΩ resistor</li><li>1 green LED</li><li>1 yellow LED</li><li>1 red LED</li><li>1 breadboard</li><li>1 Arduino and USB cable</li><li>Various connecting wires</li></ul> |

---
### Exercise 08
| Ex 09 | Electronic Dice |
| ----- | --------------- |
| Description | Create an electronic die with 6 LEDs. Your project is to light one of six LEDs randomly to mimic the throw of a die. You will create a function that chooses a random number between 1 and 6, and turn on a corresponding LED. You will have a function that selects one of six LEDs randomly and keeps the LED on for a period of time. When the Arduino running the sketch is turned on or reset, it should rapidly show random LEDs for a specified period of time and then gradually slow until the final LED is lit. The LED matching the resulting randomly chosen number will stay on until the Arduino is reset or turned off. |
| Hardware | <ul><li>6 LEDs of any color</li><li>1 560 Ω resistor</li><li>1 medium-sized breadboard</li><li>1 Arduino and USB cable</li><li>Various connecting wires</li></ul> |

---
### Exercise 09
| Ex 08 | Quick-Read Thermometer |
| ----- | ---------------------- |
| Description | Use the TMP36 temperature sensor to create a quick-read thermometor. When the temperature falls below 20 degrees Celcius, a blue LED turns on. When the temperature is between 20 and 26 degrees, a green LED turns on, and when the temperature is above 26 degrees, a red LED turns on. |
| Hardware | <ul><li>3 560 Ω resistors</li><li>1 red LED</li><li>1 green LED</li><li>1 blue LED</li><li>1 TMP36 temperature sensor</li><li>1 breadboard</li><li>1 Arduino and USB cable</li><li>Various connecting wires</li></ul> |

## Intermediate Projects
In this section you will learn:
* How to use a servo
* Use infraret and ultrasonic distance sensors
* how to control the speed and direction of electric motors
* how to use an Arduino motor shield
* begin work with a motorized  tank robot

---
### Exercise 10
| Ex 10 | Analog Thermometer |
| ----- | ------------------ |
| Description | Using a servo and the TMP36 temperature sensor, build an analog thermometer. You will measure the temperature and then convert this measurement to an angle between 0 and 180 degrees to indicate a temperature between 0 and 30 degrees Celsius. The servo will rotate to the angle that matches the current temperature |
| Hardware | <ul><li>1 TMP36 temperature sensor</li><li>1 breadboard</li><li>1 small servo</li><li>1 Arduino and USB cable</li><li>Various connecting wires</li></ul> |

### Exercise 10 - Bonus
| Ex 10 - Bonus | Distance Sensors | 
| ------------- | ---------------- |
| Description | Modify the analog thermometer you have built and implement distance sensors instead. You will use the same servo which will rotate to the angle that matches the proximity of an object to the sensor. The closer the object, the higher the rotation. Demonstrate this using an Ultrasonic Distance sensor, then an IR Distance sensor |
| Hardware | Same as above, but replace the temperature sensor with the Ultrasonic sensor, then IR sensor | 

---
### Exercise 11
| Ex 11 | Motor Control |
| ----- | ------------- |
| Description | You will now work with controlling a small electric motor. Your project will demonstrate control over the speed of a motor. You program will need to adjust the motor from still (zero) to the maximum and then reduce it back to zero. You may then try and modify this with an ultrasonic sensor. Using  the sensor, the motor should speed up and become faster the closer the object is. As the object moves away, the motor then slows down. |
| Hardware | <ul><li>1 small 3 V electric motor</li><li>1 1 kW resistor (R1)</li><li>1 breadboard</li><li>1 1N4004 diode</li><li>1 TIP120 Darlington transistor</li><li>A separate 3 V power source (i.e. a 2 cell AA battery pack)</li><li>1 Arduino and USB cable</li><li>Various connecting wires</li></ul> |

---
### Exercise 12
| Ex 12 | Building and Controlling a Tank Robot |
| ----- | ------------------------------------- |
| Description | You have now managed to build the basic components of what would be needed in a Tank Robot. It's up to you now to figure out how to build one using the knowledge you have gained. How it is controlled can be up to you, will you automate it? or do would you prefer to remote control it? At the very least, it should demonstrate movement capabilities, and collision avoidance |
| Harware | The hardware requirements will be open ended for this. You can choose to a pre-build chassis, or make a tank chassis out of toilet rolls, the choice is yours. There are some important components however: <ul><li>Arduino and USB cable</li><li>Arduino Motor Shield</li><li>Separate Alkaline AA cells</li></ul> The rest is up to you |

---
### Exercise 13
| Ex 13 | Tank Wars |
| ----- | --------- |
| Description | Now that you have built your Tank, set up a battle arena and start a tank war. Players agree on the rules, there is only one condition to pass this project. You must win. |

## Advanced Projects
Well done on getting this far! At this point, you would have learnt a lot about embedded systems already. We hope that it has inspired you with many ideas, and you feel empowered by the possibilities of what you can achieve. 

At this point, you might have many ideas of your own. You are welcome to make anything your heart desires! If you aren't sure what to do, then we have also compiled a list of ideas to get you started. You can follow them in any order you desire. Please note that we may not have all the equipment needed. You could make a suggestion to Hexagon about it. Or better yet, think about any old electronics or toys you have lying around, perhaps some of these are no longer being used? you could consider taking them apart and reusing their components for your own projects!

### Idea 01
Create an artificial general intelligence capable of beating the turing test, and writing code for you. It may take any physical form factor, so long as it can convince your evaluator that it is a conscious intelligence.

### Idea 02
Display temperature data on a Serial Monitor.

### Idea 03
Build a display that you can send texts to, and it will display the message.

### Idea 04
Build a remote-controlled car

### Idea 05
Build a self balancing motorbike

### Idea 06
Add remote control functionality to the motorbike.
