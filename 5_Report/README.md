# WATER CONTROLLER
## Abstract
- It is a simple process to detect the and indicatge the water level present in a water tank or any container.
- This circit helps to caution a person that the water tank has been filled up to certain level, but also indicates that the water level has fallen below the minimum detectable   level.
-  This circuit is important in appliances such as the water cooler where there is a danger of motor-burnout when there is no water in the radiator.
- This circuit of a water controller is designed by the number of levels and the microcontroller shows up in a display at which level the water is filled when the amount of        water is at certain level it will give some signal through buzzer to indicate a person.
- When the water-level is below the minimum detectable level (MDL), the four segment display is arranged to show the digit 0,  when the indicator shows zero then the tank is     empty, when the water reaches through any level that indicates that the water is below some level.
- For example when the water is at level 0 then water level is empty .when the water is at 4th level then the water is full so that it will give caution to a person.  

## High level requirements
- Windows(OS)
- SimulIDE Software:SimulIDE is a simple real time electronic circuit simulator, intended for hobbyist or students to learn and experiment with simple electronic circuits and     microcontrollers, supporting PIC, AVR and Arduino.
- Visual Studio Code:It is a code editor redefined and optimized for building and debugging modern web and its a source code editor made by microsoft for windows, linux, and macOS.The features of visual studio code and include support for debugging,syntax highlighting,intelligent code completion,snippets,code refactoring, and embedded Git.

## Low Level Requirements
- Microcontroller
- Sensors
- Transistor
- VCC
- Switch
- Display
- Buzzer

## Component Description
### Microcontroller
![microcontroller](https://user-images.githubusercontent.com/86915349/157207661-41ed95e5-e3e5-43a4-b24a-6648ae1c12f7.jpg)

Microcontrollers generally contain 3 timers/counters. While two 8-bit timers can also be used as counters, the third one is a 16-bit counter. These are used to generate precision output signals, count external events or measure parameters of input digital signal.
### Sensors
![sensor](https://user-images.githubusercontent.com/86915349/157209430-c7848704-ca0b-4f37-93b2-1c67593a6a40.jpg)

A sensor is a device that detects and responds to some type of input from the physical environment. The specific input could be light, heat, motion, moisture, pressure, or any one of a great number of other environmental phenomena.
### Transistor
![Transistor](https://user-images.githubusercontent.com/86915349/157209893-26e07d86-51e0-4555-a181-f64a27c57b94.jpg)

Transistor that uses both electrons and electron holes as charge carriers. In contrast, a unipolar transistor, such as a field-effect transistor, uses only one kind of charge carrier.
### VCC(voltage common collector)
VCC is the power input of a device. It may be positive or negative with respect to GND. When the only positive power supply is used then VSS (Voltage Source Supply) means ground or zero.
### Switch
![Switch](https://user-images.githubusercontent.com/86915349/157210601-b676124b-affe-4d2e-b5a5-5c383388adf0.jpg)

A switch is a piece of a physical circuitry component that governs the signal flow.
### Display
![Display](https://user-images.githubusercontent.com/86915349/157211319-187a85c1-dcdd-47c2-a42c-0ba0743fb014.jpg)

Something in a prominent place in order that it may readily be seen.
### Buzzer
![Buzzer](https://user-images.githubusercontent.com/86915349/157211664-fb266443-dede-4777-882b-c4041ccafc0f.jpg)

A buzzer or beeper is an audio signaling device, which may be mechanical, electromechanical, or piezoelectric (piezo for short). Typical uses of buzzers and beepers include alarm devices, timers, and confirmation of user input 

## 5W's & 1H
### Who
- Water controller 
### What
- A water controller is a system that realys information back to a control panel to indicate water is of ful tank or empty.
### Where
- Houses,hotels,apartments,factories etc
### When
- The purpose of the project is to manage the water levels in a water tank.
### Why
- The water controller mechanism is to detect the overhead of the water tank and the empty tank.
### How
- The water controller work by using sensors and these sensors send information to control panel to trigger an alarm(buzzer).

## SWOT Analysis
![Swot analysis](https://user-images.githubusercontent.com/86915349/157223530-e9fa8957-198f-4320-80d6-0234a0956ce3.png)
 
## Block diagram
![block diagram drawio](https://user-images.githubusercontent.com/86915349/157301527-22ce6e0b-450d-4aeb-bab2-e78010d7c909.png)

## Sequential diagram
![Sequential diagram drawio](https://user-images.githubusercontent.com/86915349/157301631-02b23f73-e64e-40bd-8222-690b03ed16c6.png)

## Activity diagram
![Activity Diagram(M2) drawio](https://user-images.githubusercontent.com/86915349/157301746-4a8c7482-887a-4655-b102-e1f2259f17ce.png)

## Flow chart
![Flowchart drawio](https://user-images.githubusercontent.com/86915349/157301828-0198a554-5273-4cf8-8813-ee0493c12a2b.png)

## Circuit diagram
![circuit diagram](https://user-images.githubusercontent.com/86915349/157302527-5743e550-6c0f-42f0-9e44-30aa38301dc6.png)

## Code
![Water controller code(M2)](https://user-images.githubusercontent.com/86915349/157303294-b9d8d605-df2d-4c86-96b5-486fb5b4a27d.png)
![Code_Water controller(M2)](https://user-images.githubusercontent.com/86915349/157303520-5293eba8-7d46-491b-a5dc-dab3979a9ad1.png)

## Test plan

Test ID     |  Description     |  Expected Output    |  Actual Output       |  Execution Type
------------|------------------|---------------------|----------------------|-------------------
T_01        | Water level is 4 | Display 4 and buzzer| Display 4 and buzzer | Technical
T_02        | Water level is 3 | Display 0 and buzzer| Display 0 and buzzer | Technical
T_03        | Water level is 2 | Display 0 and buzzer| Display 0 and buzzer | Technical
T_04        | Water level is 1 | Display 0 and buzzer| Display 0 and buzzer | Technical
T_05        | Water level is 0 | Display 0 and buzzer| Display 0 and buzzer | Technical


Test plan documentation is created.

## Output

- When the water tank is empty i.e., 0,1,2,3 levels
![Output 1 (M2)](https://user-images.githubusercontent.com/86915349/157304206-0638b877-ac32-429c-aa1f-39ef7e5f2f11.png)
- When the water tank is filled i.e., 4th level so its shows 4 and buzzer.
![Output 2(M2)](https://user-images.githubusercontent.com/86915349/157304485-6c9b04a2-f068-46e4-bcd6-187942829503.png)

 The output is captured for every possible level of requirements in test case and verified successfully














