# DESCRIPTION

## ACCIDENT ALERT SYSTEM

## INTRODUCTION

Accident alert system to rescuing people in accidents. This is improved security systems for

vehicles. The latest like GPS are highly useful nowadays. This accident alert system in it

detects the accident and the location of the accident occurred and sends GPS coordinates to

the specified mobile, computer etc.

This new technology, popularly called **ACCIDENT ALERT** Systems which created many

wonders in the security. This hardware is fitted on to the vehicle in such a manner that it is

not visible to anyone who is inside or outside of the vehicle. Thus it is used as a covert unit

which continuously or by any interrupt to the system, sends the location data to the

monitoring unit.


**ANALYSIS**

**OBJECTIVE OF PROJECT**

Accident alert system main aim is to rescuing people in accidents. This is improved security

systems for vehicles. The latest like GPS are highly useful now a day, this system enables the

owner to observe and track his vehicle and find out vehicle movement and its past activities

of vehicle.

**REQUIREMENT GATHERING**

The project requires many things: -

· **Software Requirements:**

\1. Arduino Compiler

\2. Google Maps

\3. Database

· **Hardware Requirements:**

\1. Arduino Uno

\2. Accelerometer (ADXL335)

\3. GSM Module (SIM900A)

\4. GPS Module (SIM28ML)

\5. 16x2 LCD

\6. Power Supply

**FEASIBILITY STUDY**

**Feasibility** is defined as the practical extent to which a project can be performed

successfully. To evaluate feasibility, a feasibility study is performed, which determines

whether the solution considered to accomplish the requirements is practical and workable in

the software. Information such as resource availability, cost estimation for software

development, benefits of the software to the organization after it is developed and cost to be

incurred on its maintenance are considered during the feasibility study.

**Types of Feasibility Study:**

**Technical feasibility** assesses the current resources (such as hardware and software) and

technology, which are required to accomplish user requirements in the software within the

allocated time and budget

**Operational feasibility** assesses the extent to which the required software performs a series

of steps to solve business problems and user requirements. This feasibility is dependent on

human resources (software development team) and involves visualizing whether the software

will operate after it is developed and be operative once it is installed.

**Economic feasibility** determines whether the required software is capable of generating

financial gains for an organization. It involves the cost incurred on the software development

team, estimated cost of hardware and software, cost of performing feasibility study, and so on.

**SOFTWARE DEVLOPMENT LIFE CYCLE**

SDLC describes various phases of software development and the order of execution of

phases. Each phase requires deliverable from the previous phase in a life cycle of software

development. Requirements are translated into design, design into development and

development into testing, after testing it is given to the clients.

q **REQUIREMENT PHASE**:- Requirement includes how the product will be used

and who will use the product to determine the load of operations. All information

gathered from this phase is critical to developing the product as per the customer

requirements.

q **DESIGN PHASE**:- There are several techniques and tools such as data flow

diagrams, flowcharts, decision tables and decision trees, Data dictionary, and the

structured dictionary are used for describing the system design.

q [**BUILD**](https://www.javatpoint.com/software-development-life-cycle#build-development-phase)[** ](https://www.javatpoint.com/software-development-life-cycle#build-development-phase)[/**](https://www.javatpoint.com/software-development-life-cycle#build-development-phase)[** ](https://www.javatpoint.com/software-development-life-cycle#build-development-phase)[DEVELOPMENT**](https://www.javatpoint.com/software-development-life-cycle#build-development-phase)[** ](https://www.javatpoint.com/software-development-life-cycle#build-development-phase)[PHASE**](https://www.javatpoint.com/software-development-life-cycle#build-development-phase)[** ](https://www.javatpoint.com/software-development-life-cycle#build-development-phase)[:](https://www.javatpoint.com/software-development-life-cycle#build-development-phase)- This is the coding phase it takes the

longest time and more focused approach for the developer in the software

development life cycle .

q **TESTING PHASE**:- This test plan includes all types of essential testing such as

integration testing, unit testing, acceptance testing, and system testing. Non-

functional testing is also done in this phase.

q **DEPLOYMENT / DELIVER PHASE:-** When software testing is completed with

satisfying result and there are no remaining issues in the working of software, it is

delivered to the customer for their use .

q **MAINTENANCE**  :-This phase also includes making changes in hardware and

software to maintain its operational effectiveness like to improve its performance.

This process to take care of product time to time is called maintenance.

Iterative Development model :



**COST ESTIMATION**

Software cost estimation is the process of predicting the amount of effort required to build a

software. Model provides one or more mathematical algorithms that compute cost as a

function of a number of varriable. Size is a primary cost factor in most models and can

categorized as either cost models or constraint models.

**COCOMO MODEL**

COCOMO(Constructive Cost Model) Model is a regression model based on LOC,

i.e **number of Lines of Code**. It is a procedural cost estimate model for software projects and

often used as a process of reliably predicting the various parameters associated with making a

project such as size, effort, cost, time and quality. It was proposed by Barry Boehm in 1970

and is based on the study of 63 projects, which make it one of the best-documented models.

Different models of COCOMO have been proposed to predict the cost estimation at different

levels, based on the amount of accuracy and correctness required. All of these models can be

applied to a variety of projects, whose characteristics determine the value of constant to be

used in subsequent calculations.

The Basic COCOMO model equation are:-

E=a (KLOC) ^b

D=c (E) ^d

P=E/D

Where

E= effort applied in person/mont

D= development time in critical

P=number of people

The factors for the Basic COCOMO models effort for three models these are:-

ORGANIC: - A small team of experienced developers software in a very familiar

environment.

EMBEDDED:- The project has tight constraint which might be related to the target

processor.

SEMIDETACHED:- It is an intermediate mode between the organic mode and embedded

mode.







Table of three basic cocomo model effort the factors a , b, c and d:-

**COST ESTIMATION:-**

**PARTICULARS**

**QUANTITY**

**RATE**

**AMOUNT**

No. of lines

500

Rs 1/line

Rs500

Man power

4 man,46 days

Rs50/day

Rs4,600

2hrs/day

\-

Hardware cost

Maintenance

\-

Rs1000

Rs200

Free

Rs4000

Rs1000

Rs200

Free

1year

Unit testing

Free

Testing cost

System Rent

Software cost

Rs8000

Software cost =Rs8000/-


**DESIGN**

**Block Diagram**

The block diagram of the Accident alert system is shown below. The block diagram shows

the overall view of the system. The blocks that are connected here are Microcontroller, LCD

display, GPS, GSM, Power supply.

**FIG : BLOCK DIAGRAM OF ACCIDENT ALERT SYSTEM USING GPS AND GSM**

**Circuit Diagram**


**System Flow Diagram**

Start

System Initialization

No

Accident

Yes

Accelerometer detect

Yes

No

Notification sends

Stop

Manual stop

**SOFTWARE TOOLS**

**Arduino Compiler**

The Arduino IDE is a cross-platform application written in Java, and is derived from the IDE

for the Processing programming language and the Wiring project. It is designed to introduce

programming to artists and other newcomers unfamiliar with software development. Arduino

IDE comes with a C/C++ library called "Wiring" (from the project of the same name), which

makes many common input/output operations much easier. Arduino programs are written in

C/C++.

**Google maps**

**Google Maps** is a desktop and mobi[le](http://en.wikipedia.org/wiki/Web_mapping)[ ](http://en.wikipedia.org/wiki/Web_mapping)[web](http://en.wikipedia.org/wiki/Web_mapping)[ ](http://en.wikipedia.org/wiki/Web_mapping)[mapping](http://en.wikipedia.org/wiki/Web_mapping)[ ](http://en.wikipedia.org/wiki/Web_mapping)[se](http://en.wikipedia.org/wiki/Web_mapping)rvice application and

technology provided b[y](http://en.wikipedia.org/wiki/Google)[ ](http://en.wikipedia.org/wiki/Google)[Google](http://en.wikipedia.org/wiki/Google)[,](http://en.wikipedia.org/wiki/Google)[ ](http://en.wikipedia.org/wiki/Google)offering satellite imagery, street maps, and Street

View perspectives, as well as functions such as [a](http://en.wikipedia.org/wiki/Route_planner)[ ](http://en.wikipedia.org/wiki/Route_planner)[route](http://en.wikipedia.org/wiki/Route_planner)[ ](http://en.wikipedia.org/wiki/Route_planner)[planner](http://en.wikipedia.org/wiki/Route_planner)[ ](http://en.wikipedia.org/wiki/Route_planner)[for](http://en.wikipedia.org/wiki/Route_planner)[ ](http://en.wikipedia.org/wiki/Route_planner)traveling by foot,

car, bicycle (beta test), or [with](http://en.wikipedia.org/wiki/Public_transportation)[ ](http://en.wikipedia.org/wiki/Public_transportation)[public](http://en.wikipedia.org/wiki/Public_transportation)[ ](http://en.wikipedia.org/wiki/Public_transportation)[transportation](http://en.wikipedia.org/wiki/Public_transportation)[.](http://en.wikipedia.org/wiki/Public_transportation)[ ](http://en.wikipedia.org/wiki/Public_transportation)Also supported are maps

embedded on third-party websites via the Google Ma[ps](http://en.wikipedia.org/wiki/Application_programming_interface)[ ](http://en.wikipedia.org/wiki/Application_programming_interface)[API](http://en.wikipedia.org/wiki/Application_programming_interface)[,](http://en.wikipedia.org/wiki/Application_programming_interface)[\[1\]](http://en.wikipedia.org/wiki/Google_Maps#cite_note-1)[ ](http://en.wikipedia.org/wiki/Google_Maps#cite_note-1)[a](http://en.wikipedia.org/wiki/Google_Maps#cite_note-1)nd a locator for

urban businesses and other organizations in numerous countries around the world.

Google Maps satellite images are not updated in real timeGoogle Earth support

states that most of the images are no more than 3 years old.

Shri Ram Institute of Technology Page 16





**Hardware TOOLS**

Arduino Uno R3:

Microcontroller used for our project is Arduino Uno R3.The Arduino Uno is a

microcontroller board based on the ATmega328. The ATmega328 has 32 KB (with

0.5 KB occupied by the boot loader). It also has 2 KB of SRAM and 1 KB of

EEPROM (which can be read and written with the EEPROM library). It has 20

digital input/output pins (of which 6 can be used as PWM outputs and 6 can be used

as analog inputs), a USB connection, a power jack, an in-circuit system

programming (ICSP) header, and a reset button. It is simply connected to a computer

with a USB cable. The Vin is the input voltage to the Arduino board when it's using

an external power source (as opposed to 5 volts from the USB connection or other

regulated power source). The 5V pin outputs a regulated 5V from the regulator on

the board. The microcontroller board can be supplied with power either from the DC

power jack (7 - 12V), the USB connector (5V), or the Vin pin of the board (7-12V)

**Fig.3.Arduino Uno R3**

GSM Module

SIM800 GSM module is preferred for this project for communication between accident

detector and alert system and mobile phone. It is basically tri-band work on various

frequency range (EGSM 900 MHz, DSC 1800 MHz and PCS 1900 MHz). In order to make

communicationbetween GSM mobile and arduino uno we had only used Rx pin of GSM

module and Tx pin of arduino pin.

GPS Module

SIM28ML GPS module is preferred for this project. The main function of this module is to

transmit location data to the arduino uno. The connection between arduino uno and GPS

module is set by connection transmit pin Tx of GPS to arduino uno Rx pin. This module

operates in L1 frequency (1575.42 MHz) and up to a fix territory of about 10 meters in sky,

Shri Ram Institute of Technology Page 17





itgenerates accurate information. The output of GPS module is in NMEA format which

includes data like location in real time.

**Accelerometer**

**Accelerometers** measure

such as inclination and vi

features for motion and ac

recognition, activity/inacti

r specific purposes

mbed several useful

p, single/double-tap

Shri Ram Institute of Technology Page 18





**WORKING EXPLANATION**

“Software of Accident Detection and Alert System using Arduino: The software is written in

arduino programming language and compiled in arduino IDK.” In this project, Arduino is used

for controlling whole the process with a **GPS Receiver and GSM module**. GPS Receiver is used

for detecting coordinates of the vehicle, GSM module is used for sending the alert SMS with the

coordinates and the link to Google Map. **Accelerometer namely ADXL335** is used for detecting

accident or sudden change in any axis. And an optional 16x2 LCD is also used for displaying

status messages or coordinates. **We have used GPS Module SIM28ML and GSM Module**

**SIM900A.**

When we are ready with our hardware after programming, we can install it in our vehicle and

power it up. Now whenever there is an accident, the car gets tilt and accelerometer changes

his axis values. These values read by Arduino and checks if any change occurs in any axis. If

any change occurs then Arduino reads coordinates by extracting $GPGGA String from GPS

module data (GPS working explained above) and send SMS to the predefined number to the

police or ambulance or family member with the location coordinates of accident place. The

message also contains a Google Map link to the accident location, so that location can be

easily tracked. When we receive the message then we only need to click the link and we will

redirect to the Google map and then we can see the exact location of the vehicle. **Speed of**

**Vehicle, in knots** (1.852 KPH), is also sent in the SMS and displayed on the LCD panel

Shri Ram Institute of Technology Page 19





**CODING :**

**void initModule(String cmd, char \*res, int t)**

**{**

**while(1)**

**{**

**Serial.println(cmd);**

**Serial1.println(cmd);**

**delay(100);**

**while(Serial1.available()>0)**

**{**

**if(Serial1.find(res))**

**{**

**Serial.println(res);**

**delay(t);**

**return;**

**}**

**else**

**{**

**Serial.println("Error");**

**}**

**}**

**delay(t);**

**}**

**}**

**void setup()**

Shri Ram Institute of Technology Page 20





**{**

**Serial1.begin(9600);**

**Serial.begin(9600);**

**lcd.begin(16,2);**

**lcd.print("Accident Alert ");**

**lcd.setCursor(0,1);**

**lcd.print(" System ");**

**delay(2000);**

**lcd.clear();**

**.... ......**

**...... .....**







**OUTPUT:**

**Message for accident :**

**“Accident alert”**

**latitude: 2400.0090,N**

**longitude: 12100.0000,E**

**time: 12:00”**







**TESTING**

**UNIT TEST**

Unit testing, a testing technique using which individual modules are tested to determine if

there are any issues by the developer himself. It is concerned with functional correctness of

the standalone modules.

The main aim is to isolate each unit of the system to identify, analyze and fix the defects.

UNIT TESTING is a level of software testing where individual units/ components of a software

are tested. The purpose is to validate that each unit of the software performs as designed. A

unit is the smallest testable part of any software. It usually has one or a few inputs and

usually a single output. In procedural programming, a unit may be an individual program,

function, procedure, etc. In object-oriented programming, the smallest unit is a method,

which may belong to a base/ super class, abstract class or derived/ child class. (Some treat a

module of an application as a unit. This is to be discouraged as there will probably be many

individual units within that module.) Unit testing frameworks, drivers, stubs, and mock/ fake

objects are used to assist in unit testing.

**UNIT TEST LIFE CYCLE**



SWOT-ANALYSIS

STRENGTH:-

\1. It saves the time and resources.

\2. Easy to use.

\3. Increase safety.

WEAKNESS:-

\1. Design is not so attractive.

\2. Initial training required

OPPORTUNITIES:-

\1. Can be implemented for international level.

\2. Exciting investment opportunities.

THREATS:-

1.Cost




**CONCLUSION**

Main motto of the project is to incorporate different types of sensors so that they help in

decrease the chances of losing life in such accident which we can’t stop from occurring.

Whenever accident is alerted the paramedics are reached to the particular location to increase

the chances of life. This device invention is much more useful for the accidents occurred in

deserted places and midnights. This accident alert feature plays much more important role in

day to day life in future. improves safety and security, communication medium,

performance monitoring and increases productivity. So in the coming year, it is going to play

a major role in our day-to-day living.

