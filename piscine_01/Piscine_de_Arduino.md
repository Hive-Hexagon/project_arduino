# Piscine de Arduino
*pedago: cchen@student.hive.fi*

The goal of this Piscine is to introduce you to a powerful idea. The idea that a computer is far more than the idle machines on our desks, and the servers in dark rooms. We want to convince you that computers are universal machines that can be anything you imagine. They can exist in any shape or form in the physical world, with possible functions limited only by your dreams.

Computers are the intelligence silently running the world around us. They are there in your pockets, in the air-conditioners on campus keeping you comfortable, in your cars monitoring and controlling its many internal functions. Getting food to your table, and powering your lights involves nothing short of a series of minor technological miracles in planning, transport and storage. The management of logistical networks, communication systems, electrical grids, and agrigultural production equipment all involve sophisticated computational equipment. They control the rovers currently exploring the surface of Mars, the deep-space [observatories](https://en.wikipedia.org/wiki/James_Webb_Space_Telescope) unveiling mysteries of the universe, and many other scientific instruments expanding the frontiers of knowledge. It's not that everything is carrying around armies of laptops around. Instead, most computers in the world are invisible and small "parts" embedded into the equipment we use. These are [Embedded Systems](https://en.wikipedia.org/wiki/Embedded_system). Perhaps one day, they may give rise to  synthetic creatures and [artificial life-forms](https://books.google.fi/books/about/The_Lifecycle_of_Software_Objects.html?id=8kYERQAACAAJ&redir_esc=y) that redefine what it means to be alive.

The Arduino Piscine is designed with projects that gradually increase in complexity. Since the hardware components will be reused for each project, you are instructed to record videos of your working project in action. The videos will be used for evaluations, and must demonstrate that your project works as expected.

The focus here is on learning to work with the Arduino in a weekend, we will not have strict norm requirements for the project. The idea is to give you an introduction to embedded systems, and inspire you to make amazing projects. After this Piscine, the equipment will stay on campus for you to use, we hope you will revisit your projects and continue developing them in the future.

The projects are split into [foundational](#foundation-projects) and [advanced](#advanced-projects) sections. The Foundational projects will introduce you to the basics of working with an Arduino, designing schematics, and controlling inputs and outputs. From there, you will have the option to create anything you want. If you don't know what to make, you can continue to follow the advanced projects.

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
| Hardware: | <ul><li>1 LED</li><li>1 220 Ω resistor</li><li>1 wire</li><li>1 Arduino & USB cable</li></ul> |

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

## Advanced Projects
