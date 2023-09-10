
# HarvestWalk: A Piezoelectric Approach to Powering Indoor IoT Devices

# CASA0022 for MSc Dissertation Connected Environment

**Word count : 6160**





### The Creation of HarvestWalk
[![The Creation of HarvestWalk](https://img.youtube.com/vi/Lmn2hMQN7FQ/0.jpg)](https://youtu.be/Lmn2hMQN7FQ)


# Abstract

This research delves into the design of a unique energy harvesting system using piezoelectric technology, primarily for indoor use, targeting the power needs of Internet of Things (IoT) devices. The aim is to utilise ambient mechanical energy, like human movement, to produce sustainable power.

The literature review highlights the historical role of piezoelectric materials in transforming mechanical strain into electricity, emphasising their current importance in energy harvesting. The study investigates the integration of piezoelectric elements indoors to harness energy from human actions.

Central to this research is the creation of a piezoelectric energy harvesting prototype for indoor IoT devices. The methodology encompasses the choice and assembly of piezoelectric parts to form an operational energy harvesting tile. Advanced methods, including impedance matching and maximum power point tracking, are employed to maximise energy extraction. Comprehensive experiments validate the system's feasibility. Data from real-world situations, such as foot traffic, offer insights into the system's efficacy and its potential to prolong IoT device battery life.

Additionally, the project introduces an interactive Capacitometer display, visually illustrating the energy accumulation and enhancing public understanding of piezoelectric principles. This initiative seeks to heighten awareness of energy harvesting technologies and their sustainability role. In summary, the study accentuates the value of piezoelectric energy harvesting for indoor settings, especially in bolstering IoT device power and addressing battery constraints. It adds to the renewable energy discourse, proposing a practical solution to improve the efficiency of indoor IoT devices.

 
# Introduction

This research investigates the potential application of piezoelectric tiles to harvest energy from footsteps in indoor environments. The study aims to develop a prototype system that can demonstrate the feasibility of powering Internet of Things (IoT) devices using energy generated from human movement indoors.

Piezoelectric materials possess the ability to convert mechanical strain into electrical energy through the piezoelectric effect. Integrating these elements into floor tiles enables the capture of kinetic energy when stepped on and its conversion into usable electricity. If harnessed effectively, the energy harvested could be utilised to power the numerous low-energy IoT devices increasingly deployed for smart building applications. The impetus for this research is to explore an innovative solution to meet the energy demands of indoor sensor systems and IoT devices. The current reliance on batteries for powering these systems necessitates frequent maintenance and replacement. Piezoelectric tiles present an opportunity to extract energy from the abundant and untapped source of human footsteps to operate IoT devices sustainably.

Through rigorous experimentation, this study aims to design, develop and evaluate a functioning prototype of a piezoelectric energy harvesting tile system. The research will assess the quantity of electrical energy that can be generated from footsteps using the prototype. Additionally, it will examine techniques to effectively store and utilise the harvested energy. The overarching objective is to determine the feasibility of the system for real-world deployment.

The research outcomes will contribute knowledge regarding sustainable power sources for IoT devices deployed indoors. If proven successful, the piezoelectric tile technology could potentially enhance energy efficiency in buildings and reduce the environmental impact of frequent battery replacement. The project seeks to provide a practical solution that promotes smart infrastructure through renewable energy principles.


# Literature Review


2.1 Introduction to Piezoelectric Tiles for Energy Harvesting
The use of piezoelectric tiles for indoor energy harvesting is a promising yet challenging approach to sustainable power generation. The concept of converting mechanical energy from footsteps into electrical energy, while innovative, is a familiar idea (Li and Strezov, 2014; Sharpes et al., 2016). The utilisation of a piezoelectric idea as a plentiful but previously untapped energy resource dates back to as early as 1880.  It was pioneered by the Curie brothers, Pierre and Jacques, who laid the groundwork for this transformative approach(Woodford, 2009).

**2.2 The Potential of Piezoelectric Technology**

Piezoelectric technology is widely recognised for its potential as a sustainable energy source for small devices (Sharpes et al., 2016; Covaci and Gontean, 2019). Various strategies, such as the implementation of piezoelectric tiles and floors, have been examined to harness mechanical vibrations and transform them into electrical energy (Sharma et al., 2022; Hwang et al., 2015).

**2.3 Applications of Piezoelectric Energy Harvesting**

Piezoelectricity refers to the property of certain materials to generate an electrical charge when mechanically stressed. This effect is detailed in Shreeshayana et al. (2017), which provides an in-depth explanation of how a piezoelectric generator functions, including a diagram of the piezoelectric effect see figure 1 for the detailed diagram.

![Figure 1 Piezoelectric Effect](https://raw.githubusercontent.com/Gil-ADDA/Piezoelectric-Energy-Generation-HarvestWalk/b973fc076b7be44e6545e34c5a0c585f3008376f/Project%20Figures%20Tables%20and%20Diagram/Figure%201%20Piezoelectric%20Effect.png)



Piezoelectric materials can harness electrical energy in areas with high pedestrian traffic. By converting the mechanical energy from foot pressure on pavements into electrical power, this energy can be used to power Internet of Things (IoT) devices, stored in batteries for later use, or contribute to larger systems to reduce fossil fuel consumption. The energy generated from steps on piezoelectric tiles can estimate potential energy in high pedestrian traffic areas (Pattipaka et al., 2022). However, it's crucial to consider the environmental implications of the batteries used in this technology. Utilising the piezoelectric effect, energy harvesters can extend battery life and reduce maintenance needs (Sodano, Inman, & Park, 2005).

**2.4 IoT Devices in Smart Buildings**

In scenarios where the purpose and ownership of buildings change, there is a crucial need for consistent environmental data collection. A key element in realising smart building concepts is the efficient and flexible deployment of IoT devices (Covaci and Gontean, 2019). These devices, requiring low energy, are designed to collect ambient data from various indoor environments, including offices, factories, homes, and more (Sharpes et al., 2016; Kim et al., 2018).
Importantly, these devices can operate independently of the grid, eliminating the need for wired connections (Jawahar et al., 2021). This autonomous operation not only bolsters the capability to monitor and enhance energy usage but also assists in the early detection of infrastructure issues (Godard et al., 2020). Moreover, it aids in understanding the occupancy usage of facilities, detecting air pollution, among other benefits. Thus, deploying off-grid IoT devices might represent a significant step towards the broader adoption of smart building technologies (Li and Strezov, 2014; Shanmugam et al., 2020).

**2.5 Real-world Implementations of Piezoelectric Technology**

The Smart Tile Energy Production Technology (STEP Tech) project serves as a compelling illustration of the piezoelectric effect's capability to harness energy from footsteps (Sharpes et al., 2016). This could represent a significant stride towards the realisation of smart building concepts. This particular technology, which operates independently of grid or battery power, employs a floor tile energy harvester to establish a wireless, self-powered occupancy sensor. The STEP Tech system is designed to automate and regulate various functionalities in smart buildings, such as lighting and climate control, in response to real-time occupancy data (Sharpes et al., 2016).

In addition to the Smart Tile Energy Production Technology (STEP Tech), there are other noteworthy products on the market that utilise the piezoelectric effect for energy generation from footsteps. For example, the Waynergy Floor, suitable for both indoor and outdoor environments, powers lighting and security systems in areas with high foot traffic (Department of Architecture Engineering, BUE, 2021). The Sustainable Energy Floor (SEF) employs customisable tiles to energise road lights and signage in pedestrian-heavy zones (Elhalwagy et al., 2017).

Furthermore, Pavegen Tiles finds applications across diverse sectors, encompassing train stations, shopping centres, and airports. These tiles have the capacity to energise interactive displays and signage, and they can interface with an array of mobile devices and building management systems (Elhalwagy et al., 2017; Department of Architecture Engineering, BUE, 2021). Collectively, these products underscore the expansive potential and adaptability of piezoelectric technology across varied contexts (Solban and Moussa, 2021).

**2.6 Challenges and Considerations**

The practicality and efficiency of this system on a large scale remain under scrutiny (Li and Strezov, 2014). Whilst the energy produced is adequate to power low-energy Internet of Things IoT devices, its contribution to the overall energy requirements of a building may be relatively minor (Shanmugam et al., 2020).
Furthermore, the initial costs and upkeep of these systems could present considerable challenges (Elhalwagy et al., 2017; Department of Architecture Engineering, BUE, 2021). Notwithstanding these challenges, the incorporation of piezoelectric technology into buildings signifies a progressive approach to energy efficiency and sustainability, particularly as the technology continues to advance (Sodano et al., 2005; Li and Strezov, 2014; Sharpes et al., 2016; Elhalwagy et al., 2017).

**2.7 Research Focus and Objectives**

This research project centres on exploring a solution to the energy demands of indoor environmental monitoring systems by utilising the piezoelectric effect. The study examines the potential to extract energy from human footsteps through tiles equipped with piezoelectric sensors. Such energy has the capacity to power low-energy computer systems, such as microcontrollers, which are fundamental to the operation of numerous contemporary technologies. By harnessing the energy derived from human footsteps, there exists a potential to enhance the lifespan of these devices, reduce their reliance on conventional power sources, and bolster overall energy efficiency.

**2.8 Github Link**

All codes utilised for the exhibition, voltage measurements, as well as the documents detailing the designs in Fusion 360, can be accessed via the following link: https://github.com/Gil-ADDA/Piezoelectric-Energy-Generation-HarvestWalk .
Inspiration
Can you imagine a world where all IoT devices run on renewable energy without the need for batteries? Currently, these devices require energy to run their programs and collect real-time data. The realisation of supplying power to every IoT device and securing their connectivity to the communication network is critical. Hence, I became highly motivated to undertake this project. The idea for this project came from a company called Pavegen, which produces energy from footsteps and collects data on pedestrian traffic. I was inspired by the concept of generating renewable energy in a way that I did not fully understand before, and also by the potential for my colleagues to use this technology to power their projects independently of the electricity grid (Pavegen, 2022).

After conducting extensive research and discovering that it is feasible to charge phones or power temperature sensors and transmit data via Bluetooth, I became persuaded of my capability to formulate it independently. Upon consulting with my Supervisor, Dr.Valerio Signorelli , I realised that it was an attainable goal. Furthermore, I would be able to generate energy and might gather data on pedestrian traffic.
Ultimately, the concept that the piezo tile has the potential to generate sufficient energy to power IoT devices resonates with me the most. (Paul et al., 2015)


** Methodology **
In the 'Inspiration' segment, reference was made to the pioneering work of the Pavegen company, which subsequently instigated an in-depth investigation into piezoelectricity. The paramount aim of this scholarly endeavour is to extract energy from pedestrian movements within enclosed spaces. This extracted energy is destined to energise an advanced microcontroller, equipped with sensors specifically for temperature and infrared motion detection. The data, once collated, is designed to be conveyed through established IoT mediums, including but not limited to Bluetooth and Wi-Fi. The 'Methodology' section offers a detailed chronicle of the three distinct prototype iterations, coupled with an analytical breakdown of the mathematical formulations utilised. This section also provides insight into the assembly of the capacitometer and the mechanisms of energy transmutation
**4.1 Fabrication Work**

Layers of the tile: 
![Diagram 1 HarvestWalk Piezo Circuit Layers](https://raw.githubusercontent.com/Gil-ADDA/Piezoelectric-Energy-Generation-HarvestWalk/7aa8df6b5083085d6f1d4e4a56296f210bd80c80/Project%20Figures%20Tables%20and%20Diagram/Diagram%201%20HarvestWalk%20Piezo%20Circuit%20Layers.png)


**4.2 Iteration 1**
Firstly, construct the initial version of the tile using 20 piezo discs. Proceed to build the bridge rectifier (See Figure 2) in order to convert the AC voltage to DC voltage (See Diagram 1), then use a multimeter to measure the amount of DC voltage output (See Figure 3). Confirm that the tile is able to generate energy successfully.
![Figure 2-3 and Diagram 2 Role of Bridge Rectifier](https://raw.githubusercontent.com/Gil-ADDA/Piezoelectric-Energy-Generation-HarvestWalk/7aa8df6b5083085d6f1d4e4a56296f210bd80c80/Project%20Figures%20Tables%20and%20Diagram/Figure%202-3%20and%20Diagram%202%20Role%20of%20Bridge%20Rectifier.png)


In an experiment, a tile equipped with 20 piezo discs was tested for its voltage generation capabilities. The results showed that the tile could produce a voltage of 1.200 volts when connected to a bridge rectifier and a 1000 microfarads capacitor. However, a significant challenge in harnessing energy from piezoelectric materials is the conversion from AC to DC voltage. Using a standard bridge rectifier for this conversion results in a substantial energy loss. Consequently, it was deduced that a more efficient circuit would significantly enhance piezoelectric energy harvesting (Covaci and Gontean, 2021). 

The process of constructing piezo circuit tiles primarily involved a series of hands-on experiments. The initial phase involved measuring the voltage generated by various piezo types and the resulting DC voltage produced see video 1.
[![Video 1](https://img.youtube.com/vi/eATSxM-Sl1c/0.jpg)](https://youtu.be/eATSxM-Sl1c)

The construction of a bridge rectifier followed this see figure 2 above designed to convert AC voltage to DC, stabilize the electrical wave, and facilitate the measurement of the DC voltage. A 1000-microfarad capacitor was then connected, and a series of measurements were taken to determine the charge generated at each stage and the total charge accumulated in the capacitor.
It was noted that the capacitor exhibited a leak, prompting an investigation into potential causes and subsequent solutions. This necessitated an examination of the feasibility of storing the energy produced by the tile without considerable loss over time. Consequently, I sought a more efficient circuit and ultimately identified the LTC-3588-1 chip (Ching et al., 2018).

Initially, the DC voltage across the capacitor was assessed using an Arduino UNO rev wifi2. This method revealed a limitation inherent to the Arduino board: while attempting to read the voltage values of the capacitor, the Arduino inadvertently drew power from it. As the Arduino operates at 5 volts and 12 bits, it was unable to accurately measure voltage values that exceeded its own operational parameters without affecting the capacitor's charge(Arduino, n.d.). Due to this interference, the method was deemed unsuitable for obtaining precise voltage readings from the capacitor.
In examining voltage dividers, it became evident that they can divide or reduce voltage levels using resistors, the optimal values of which can be deduced through mathematical analysis (Fransiska et al., 2013). An attempt was made to craft an AC voltage divider to assess the voltage across the capacitor. Regrettably, this initiative faced difficulties. The root of these complications was the intrinsic unsuitability of voltage dividers for AC voltage, given that AC voltage alternates between positive and negative values, which are undetectable by the Arduino UNO rev wifi2 when interfaced with the piezo.



Subsequently, I embarked on constructing a DC voltage divider for the capacitor. Utilising the conventional voltage divider formula:
Vout = Vin * (R2 / (R1 + R2))
resistances of 30 kilo-ohms and 5 kilo-ohms were employed on the respective sides. This classical approach allows for precise determination of input and output voltages.
To ascertain the maximum input voltage this divider can handle while the Arduino reads a maximum of 5 volts, one can rearrange the formula to:
Vin = (Vout * (R1 + R2)) / R2
Given the resistances provided, the divider can accommodate an input voltage of up to 175 volts. (An illustrative image can be found below.)
In the realm of electronics, voltage dividers play a pivotal role in adjusting voltage levels to desired values. These dividers employ resistors to achieve the desired voltage reduction. The fundamental principle behind a voltage divider is encapsulated in the formula:
Vout = Vin x (R2 / (R1 + R2))
Where Vout is the output voltage, Vin is the input voltage, R1 is 30kΩ, and R2 is 15Ω.
Given the scenario of reading an AC voltage from a piezo disc that can reach up to 20 volts using an Arduino with a 5-volt limit, a voltage divider becomes indispensable. By judiciously selecting the resistor values, one can ensure that the Arduino reads a voltage within its permissible range, even when the piezo disc produces its maximum output.
![Figure 4-5](https://raw.githubusercontent.com/Gil-ADDA/Piezoelectric-Energy-Generation-HarvestWalk/7aa8df6b5083085d6f1d4e4a56296f210bd80c80/Project%20Figures%20Tables%20and%20Diagram/Figure%204-5.png)



**4.3 Iteration 2**
The circuit design was inspired by an analysis of "Powering Lights with Piezoelectric Energy-Harvesting Floors" by Puscasu et al. (2018). The design detailed in the article appeared amenable for implementation. The tile circuit measures 300 by 300 (refer to imageX). For the HarvestWalk project, a total of 100 piezo discs were utilised, all connected in parallel. These discs, with their positive and negative terminals, employ copper foil to harness energy, reminiscent of an AC voltage circuit. Each disc is situated on copper foil at the piezo's negative terminal and the silicon piece. Above the piezo, a perforated sticker is placed, allowing the copper foil to access the positive terminal. This is further covered with a copper foil strip, which is subsequently protected by an additional layer to counteract wear and tear from repeated impacts (refer to image!). Each terminal is connected using a distinct cable, ensuring all piezos are linked in parallel across both positive and negative terminal layers. All copper foil strips are connected to a single output, which then links to the ltc3588-1 harvesting chip (See Figure 6).
Beneath the tile, a layer of flexible wood was introduced, allowing the piezo transducer to deflect by 2mm when stepped upon. This was further protected by an acrylic layer from above. Subsequent research underscored the efficacy of energy harvesting with piezoelectricity, especially when employing the SSHI (Synchronized Switch Harvesting on Inductor) method. This revelation prompted the exploration of the LTC-3588-1 chip by Linear Technology Analog Devices, which boasts a Low-Loss Full-Wave Bridge Rectifier and an impressive 90% efficiency (Analog Devices, n.d.). 

![Figure 6 LTC-3588-1 Chip](https://raw.githubusercontent.com/Gil-ADDA/Piezoelectric-Energy-Generation-HarvestWalk/58f8cb5b9eed0f05e20cc7eaa3727496cc4d78dd/Project%20Figures%20Tables%20and%20Diagram/Figure%206%20LTC-3588-1%20Chip.png)
 ![Figure 7-8](https://raw.githubusercontent.com/Gil-ADDA/Piezoelectric-Energy-Generation-HarvestWalk/58f8cb5b9eed0f05e20cc7eaa3727496cc4d78dd/Project%20Figures%20Tables%20and%20Diagram/Figure%207-8%20.png)


 
** 4.4 Iteration 3**
In this advanced iteration of the tile, a total of 100 piezo discs are utilised, segmented into 40 discs measuring 35mm and 60 discs at 27mm (see Figure 9). The foundational layer of the circuit is a transparent, flexible plastic, precisely laser-cut to a 300mm by 300mm dimension. Atop this lies a copper foil, specifically allocated for the negative terminal. Once the black wire is soldered to this terminal, the piezo discs are methodically placed over it. To prevent any unintended contact with the positive terminal of the piezo, a laser-cut transparent sticker, perforated for precision, is applied (see Figure 10). Following this, the positive terminal is sheathed with copper foil, and the red wire is affixed via soldering. To ensure the durability of the assembly, a protective transparent sticker is wrapped around the entire circuit, shielding the copper foil.

![Figure 9](https://raw.githubusercontent.com/Gil-ADDA/Piezoelectric-Energy-Generation-HarvestWalk/58f8cb5b9eed0f05e20cc7eaa3727496cc4d78dd/Project%20Figures%20Tables%20and%20Diagram/Figure%209.png)

![Figure 10](https://raw.githubusercontent.com/Gil-ADDA/Piezoelectric-Energy-Generation-HarvestWalk/58f8cb5b9eed0f05e20cc7eaa3727496cc4d78dd/Project%20Figures%20Tables%20and%20Diagram/Figure%2010.png)


 
 
 Transitioning to the acrylic circuit tiles, they are seamlessly interfaced with the LTC-3588-1 via PZ1 and PZ2, all housed on a wooden box tile. The integration of the LTC-3588-1 onto a PCB is complemented by the addition of capacitors: a 10 µF on the input and a 2200 µF on the output.

The subsequent phase of the assembly process involves the integration of auxiliary circuit components. This includes the Arduino and a pair of push buttons. These buttons are distinctively crafted from two PCB boards with an interposed sponge and a modicum of soldering see figure 11 below. On one side of the button, a pin is connected to the GND, whilst the other side is affixed to a digital pin. To be precise, the primary button is connected to both the GND and the digital pin number 2. Its counterpart, the secondary button, is analogously connected to the GND and digital pin number 3. Additionally, the Capacitometer wires are incorporated into this configuration, establishing connections to the Arduino's digital pin number 6, the GND pin, and, ultimately, the 5V pin. For a visual elucidation and further inspiration, one might consult the image below and reference the DIY Force Sensitive Resistor (FSR) project, which served as a foundational inspiration for this endeavour (McDonald, 2008)
![Figure 11](https://raw.githubusercontent.com/Gil-ADDA/Piezoelectric-Energy-Generation-HarvestWalk/dcd527dce74ef9285a8fc9ed8a959074b1aca608/Project%20Figures%20Tables%20and%20Diagram/Figure%2011.png)


**4.5 Fabrication Process: Utilising Laser Cutting Techniques**

Design & Software: The primary method utilised for the fabrication of the 'HarvestWalk' project was laser cutting. This technique was chosen for its precision and its compatibility with the Fusion 360 design software. The design was meticulously crafted in Fusion 360, ensuring its suitability for the laser-cutting process. It was then exported in the DXF format to ensure seamless integration with the laser cutting apparatus.
4.5.1 Material Considerations
In the initial stages of the project, an attempt was made to incorporate a rug or rubber mat as a covering for the piezoelectric circuit to simulate a more realistic environment. However, the decision to modify the design was driven by aesthetic considerations. The aim was to seamlessly integrate a rug or rubber mat with the piezo flooring, ensuring that the entire electrical circuit, inclusive of the Arduino board and button wires, could be neatly and aesthetically housed in one place. 
For visual references, please see the Figures 12 and 13 below.



![Figure 12-13](https://raw.githubusercontent.com/Gil-ADDA/Piezoelectric-Energy-Generation-HarvestWalk/dcd527dce74ef9285a8fc9ed8a959074b1aca608/Project%20Figures%20Tables%20and%20Diagram/Figure%2012-13.png)


** 4.5.2 Dimensions **
The base, measuring 400mm x 400mm, supports four wooden sides or walls. These walls, in turn, support a cover that features two holes designed for the placement of pressure buttons. Atop this cover sits the piezo floor with its electrical circuit. An additional frame, measuring 400mm x 400mm, is placed on top of the piezo floor. This frame, with its central void measuring 350mm x 350mm, was added not only to allow exhibition attendees to view the piezo discs but also to ensure the stability of the electrical circuit. The circuit was observed to move frequently on the floor, which could have potentially damaged it and inconvenienced users during the exhibition.
4.5.3 Equipment
12-millimetre wood
Tortec laser cutting machine
Gorilla wood glue

**4.5.4 Procedure**
Laser Cutting Execution: 
Utilising the laser cutting machine, precise incisions were made on the 12-millimetre wood. The design blueprint incorporated spaces specifically for the piezo discs elegantly showcased within the top frame. Engravings on this frame include "Charge me", "Jump on and bounce for renewable energy", and "HarvestWalk" see figure 14 below.

 ![Figure 14](https://raw.githubusercontent.com/Gil-ADDA/Piezoelectric-Energy-Generation-HarvestWalk/dcd527dce74ef9285a8fc9ed8a959074b1aca608/Project%20Figures%20Tables%20and%20Diagram/figure%2014.png)





**4.5.5 Assembly: **
After the laser cutting phase, the wooden components were meticulously assembled. The four walls were both glued and screwed to the wooden base for added strength and stability. The cover was then placed atop these walls. The piezo floor, with its electrical circuit, was subsequently positioned on the cover, followed by the placement of the top frame.
**4.5.6 Supplementary Features:**
Cable Management: Strategically positioned holes were incorporated for efficient cable management for the Arduino, LED, LTC-3588-1 chip, and AC Voltage measurements with the oscilloscope.

**4.5.7 Capacitometer:**
 The "Capacitometer", made using a similar laser cutting method, features an engraving on the acrylic segment indicating the battery's charge percentage. The background, made of 10mm thick wood, was engraved to a depth of 2mm to create a space for the LED. The energy stored in Coulombs was also engraved on the wood.
Additionally, a transparent acrylic piece, 5mm thick, was laser-cut in the shape of a battery and engraved with indicators for 25%, 50%, 75%, and 100% battery charge.
Stand: The stand, visible in the accompanying image, was crafted from recycled workshop materials. This was done to ensure that the LED and the floor were at the same height, providing a uniform appearance for the exhibition.

![Figure 15](https://raw.githubusercontent.com/Gil-ADDA/Piezoelectric-Energy-Generation-HarvestWalk/dcd527dce74ef9285a8fc9ed8a959074b1aca608/Project%20Figures%20Tables%20and%20Diagram/Figure%2015.png)


**5. Design and Schematic of HarvestWalk exhibition Circuit**
This schematic represents a modified version of a circuit designed for an exhibition. Several modifications were made to simplify the original design. The circuit includes an LED strip consisting of 58 LEDs. It is important to note that the LTC-3588 chip and the Arduino Uno WiFi Rev 2 are not interconnected in this design. Additionally, the LTC circuit includes a switch, which is connected to a small LED. However, the representation of this switch and LED on the schematic is quite small and may be difficult to discern


![Figure 16](https://raw.githubusercontent.com/Gil-ADDA/Piezoelectric-Energy-Generation-HarvestWalk/dcd527dce74ef9285a8fc9ed8a959074b1aca608/Project%20Figures%20Tables%20and%20Diagram/Figure%2016.png)


**6. Experiments **
6.1 Floor Experiments
It's essential to note that the experiments involving the floor were carried out by jumping on it. This was done to increase the load on the piezoelectric discs, producing higher vibrations and more strain, aiming to extract the maximum energy within the given time frame. Additionally, some tests were performed on the floor with a rubber mat to simulate real-world conditions Figure 12 above. However, these tests yielded lower energy outputs, leading to the decision to keep the floor exposed to as much vibration and pressure as possible without any intervening layers.

**6.2 Energy Conversion** 

Initially, a bridge rectifier was constructed to convert the AC energy from the piezoelectric material to DC. The voltage output from the piezoelectric material was then measured. Subsequently, capacitors of various sizes (1000 microfarads, 470 microfarads, and 2200 microfarads) were connected to determine the amount of energy stored and whether it was sufficient to power an LED. When working with the bridge rectifier, there was a rapid energy dissipation. Even if the LED lit up, it was so dim that it was barely visible.
Further academic research on energy conversion and harvesting from piezoelectric materials was conducted. This led to the discovery of a method and, subsequently, a chip that could harvest energy with 90% efficiency (Godard et al., 2020; De Fazio et al., 2021). As mentioned on pages 12-13 of the datasheet for the LTC-3588-1 chip, a 10 µF capacitor was recommended for the input. Following this guidance, a 10 µF capacitor was utilised at the input. For the output, a series of experiments were conducted using capacitors ranging from 470 microfarads to 0.22 farads. The results of these experiments, detailing the efficiency of energy storage and the duration an LED could be powered, will be presented in the table below(Analog Devices, n.d.).




**6.3 Microprocessor Integration**

After successfully powering the LED, the next step was to find microprocessors that could read data, such as temperature or humidity, and communicate via Bluetooth. Due to the limited time available to complete the project and the need to prepare for an exhibition, this result was finalised. However, several studies have demonstrated success in powering electrical circuits through the movement of piezoelectric materials, which will be elaborated upon in the discussion section.
Link for the experiment see video 2 with the capacitor 0.22 F


![Table 1 Experiments](https://raw.githubusercontent.com/Gil-ADDA/Piezoelectric-Energy-Generation-HarvestWalk/28045c1409424383080527edc3bb8bb507bd9a4a/Project%20Figures%20Tables%20and%20Diagram/Table%201%20Experiments.png)







[![Video 2](https://img.youtube.com/vi/flG9PlelOzI/0.jpg)](https://youtu.be/flG9PlelOzI)



![Figure 17 AC Voltage Measurements of Tile Version 2 Using Oscilloscope](https://raw.githubusercontent.com/Gil-ADDA/Piezoelectric-Energy-Generation-HarvestWalk/dcd527dce74ef9285a8fc9ed8a959074b1aca608/Project%20Figures%20Tables%20and%20Diagram/Figure%2017%20AC%20Voltage%20Measurements%20of%20Tile%20Version%202%20Using%20Oscilloscope.png)



**7. Calculation**
**7.1 Analysis of Current Flow Through a Capacitor in Piezo Tile Experiment**

In the course of our experimentation to assess the efficiency of the piezo tile, a detailed analysis was conducted to determine the current flowing through a capacitor in our experimental setup. The capacitor in question had a capacitance of 470 microfarads and was subjected to a voltage of 3.3 volts. The relationship between current (I), capacitance (C), and voltage (V) is given by the formula:

I = C * (dV/dt).

Substituting in the given values, the calculation was:

I = 470 * 10^-6 F * (3.3 V / 1 s) = 0.0005 A.

This calculation yielded a current of 0.0005 amperes, which is equivalent to 0.5 milliamps. This analysis elucidates the relationship between voltage, capacitance, and current, providing a deeper understanding of the electrical behaviour exhibited in piezo tile experiments. The insights obtained from this are invaluable for the optimisation of devices in practical applications.

For a visual representation of the step-by-step calculation process, please refer to the whiteboard illustration provided in Figure 18. Additionally, the calculations were cross-verified using the online tool.

![Figure 18 Calculate the Amount of Charge](https://raw.githubusercontent.com/Gil-ADDA/Piezoelectric-Energy-Generation-HarvestWalk/dcd527dce74ef9285a8fc9ed8a959074b1aca608/Project%20Figures%20Tables%20and%20Diagram/Figure%2018%20Calculate%20the%20Amount%20of%20Charge.png)


**7.2 Measurement Tools Employed**
Multimeter: Used primarily for measuring DC voltage.
Oscilloscope: Employed for measuring AC voltage.
Charge Measurement: Quantifying the amount of charge.
Power Measurement: Determining the number of watts.
Energy Measurement: Assessing the amount of energy in joules.
Current Measurement: Gauging the amount of current in milliamperes.

![Table 2 Tools and Calculation Description](https://raw.githubusercontent.com/Gil-ADDA/Piezoelectric-Energy-Generation-HarvestWalk/28045c1409424383080527edc3bb8bb507bd9a4a/Project%20Figures%20Tables%20and%20Diagram/Table%202%20Tools%20and%20Calculation%20Description.png)


**7.3 Experimental Procedure**
The experiment involved participants jumping on the tile. The duration of the activity, the number of jumps required to charge the capacitor to 3.3 volts, and other pertinent details will be discussed in subsequent sections.


![Table 3 Calculation Values](https://raw.githubusercontent.com/Gil-ADDA/Piezoelectric-Energy-Generation-HarvestWalk/28045c1409424383080527edc3bb8bb507bd9a4a/Project%20Figures%20Tables%20and%20Diagram/Table%203%20Calculation%20Values.png)


Capacitor Charging Experiment: Summary of Results

The capacitance of the capacitor is 2200 microfarads, and it is charged to a voltage of 3.3 volts.
The energy stored in the capacitor can be calculated using the formula E = (1/2) * C * V^2, which gives approximately 11.99 millijoules.
The time taken to charge the capacitor is 3 minutes and 10 seconds, which is equivalent to 190 seconds.
The power associated with charging the capacitor can be calculated using the formula P = E / t, which gives approximately 63.1 microwatts.
The charge transferred to the capacitor can be calculated using the formula Q = C * V, which gives approximately 7.26 millicoulombs.
The average current associated with charging the capacitor can be calculated using the formula I = Q / t, which gives approximately 38.2 microamperes.
During the experiment, a participant with a weight of 80 kg performed jumps on a tile. It took 280 jumps to achieve this.

**8. Code**
The code for the project involving the hardware Arduino Rev 2 WiFi was initially structured to encompass two distinct sections. The first section aimed at reading voltage data from the LTC-3588-1 chip's capacitors input and output and transmitting it to ThingSpeak for storage. However, initial attempts yielded less-than-ideal results, prompting a tailored code adjustment to better meet the needs of the forthcoming exhibition. The second section concentrated on the exhibition itself, necessitating the communication of pre-collected data and creatively visualising energy dynamics through user engagement. Specifically, this involved capturing button presses, which in turn illuminated the concept of energy storage and generation via a mechanical force applied to a piezo tile.




**8.1 Chapter 1: Voltage Readings and Data Transmission**

This segment of the code revolves around voltage measurements and data transmission. The primary objective is to acquire precise DC voltage readings both across the input (Vin) and output (Vout) of the LTC-3588-1 chip's capacitor See sections 1-2 in table 4 below. Additionally, the code endeavors to measure the AC voltage at the output (Vout piezo) originating from the piezoelectric tile See section 3 in the table 4 below. Subsequently, the gathered voltage data is intended to be uploaded to ThingSpeak, an IoT platform, for store and analysis the data.
Access to the code chapter 1
- [Exhibition Code (Without reading Voltages (in and out) and without sending data to ThinkSpeak)](https://github.com/Gil-ADDA/Piezoelectric-Energy-Generation-HarvestWalk/blob/7295c67905b1bed97f45a55a4a08c93202d78824/code/Exhibition%20Code%20%20(Without%20reding%20Voltages%20(in%20and%20out)%20and%20without%20sending%20data%20to%20ThinkSpeak))


**8.2 Chapter 2: Energy Visualization and Gamification**

In this phase, the focus shifts toward creating an engaging exhibition experience. The aim is to communicate the previously collected voltage data effectively. The number of button presses—registered from both the right and left buttons—serves as an innovative representation of the energy stored in the 2200 microfarad capacitor. This visual portrayal is facilitated by illuminating a set of 56 LEDs, thus offering visitors an intuitive understanding of energy accumulation. Furthermore, the incorporation of a piezo tile demonstrates the concept of energy generation via mechanical force, aligning with the project's educational aspirations.

- [Press Buttons and voltage measurements](https://github.com/Gil-ADDA/Piezoelectric-Energy-Generation-HarvestWalk/blob/7295c67905b1bed97f45a55a4a08c93202d78824/code/Press%20Buttons%20and%20voltage%20measurements)
Access to the code chapter 2

![Table 4 Code Description](https://raw.githubusercontent.com/Gil-ADDA/Piezoelectric-Energy-Generation-HarvestWalk/28045c1409424383080527edc3bb8bb507bd9a4a/Project%20Figures%20Tables%20and%20Diagram/Table%204%20Code%20Description.png)

![Table 5 Library Description](https://raw.githubusercontent.com/Gil-ADDA/Piezoelectric-Energy-Generation-HarvestWalk/28045c1409424383080527edc3bb8bb507bd9a4a/Project%20Figures%20Tables%20and%20Diagram/Table%205%20Library%20Description.png)

![Table 6 Button Press Variables Schema in the System](https://raw.githubusercontent.com/Gil-ADDA/Piezoelectric-Energy-Generation-HarvestWalk/28045c1409424383080527edc3bb8bb507bd9a4a/Project%20Figures%20Tables%20and%20Diagram/Table%206%20Button%20Press%20Variables%20Schema%20in%20the%20System.png)


![Figure 19 and Table 7](https://raw.githubusercontent.com/Gil-ADDA/Piezoelectric-Energy-Generation-HarvestWalk/28045c1409424383080527edc3bb8bb507bd9a4a/Project%20Figures%20Tables%20and%20Diagram/Figure%2019%20and%20tabel%207.png)

![Figure 20-21 and Table 8](https://raw.githubusercontent.com/Gil-ADDA/Piezoelectric-Energy-Generation-HarvestWalk/28045c1409424383080527edc3bb8bb507bd9a4a/Project%20Figures%20Tables%20and%20Diagram/Figure%2020-21%20and%20table%208%20.png)

**8.5 Algorithm of the HarvestWalk - Exhibition code**
The flowchart outlines the logic of an Arduino sketch designed to control a strip of LEDs based on the number of button presses. The sketch operates in a continuous loop, initially checking the state of the first button. If pressed, the program updates the press count, combined press count, and the LED strip accordingly. Subsequently, the program checks if the cumulative count of both button presses has reached a predefined threshold (260). If so, it resets the counters and switches off the LEDs. The program then proceeds to check the state of the second button, following a similar logic. If the second button is pressed, the program updates the press2 count, combined press count, and the LED strip. The program then checks again if the cumulative count has reached the threshold, and if so, resets the counters and switches off the LEDs. This process continues indefinitely, providing a dynamic and interactive way to control the LED strip see diagram 3 below.

![Diagram 3 Algorithm flowchart](https://raw.githubusercontent.com/Gil-ADDA/Piezoelectric-Energy-Generation-HarvestWalk/ad374ace69ed69d8ef3663eaa5316ba4c4104757/Project%20Figures%20Tables%20and%20Diagram/Diagram%203%20Algorithm%20flowchart.png)


**9. Electronic Component Choices**



![Table 9 Electronic Component](https://raw.githubusercontent.com/Gil-ADDA/Piezoelectric-Energy-Generation-HarvestWalk/ad374ace69ed69d8ef3663eaa5316ba4c4104757/Project%20Figures%20Tables%20and%20Diagram/Table%209%20Electronic%20Component.png)

 
** 10. Visualisation and communication**

Building the LED-Capacitometer
Influenced by Hudson-Smith's Neopixel Barometer, the Capacitometer was developed (Hudson-Smith, 2022). This device, often referred to simply as the Capacitometer, utilises LEDs to visualise data, complemented by intricate designs crafted from laser-cut acrylic and wood. The primary motivation behind its creation is to effectively communicate and visualise the energy generated by the HarvestWalk tile. This apparatus seamlessly marries contemporary technology with classical design elements, aiming to render the complex charging data of a capacitor into a format that is both visually compelling and straightforward for any user to comprehend
The Capacitometer is an essential tool for gauging and monitoring the energy output of the tile, offering a lucid perspective on its performance. As can be seen in the segment explaining the code, the brightness of the LEDs and the lights are activated when two floor pressure buttons are pressed. Both the buttons and the LEDs are connected to an Arduino board. Upon detecting a press on one of the pressure buttons, the LED increases its brightness level. There are 58 LEDs in total. When the button is pressed for the first time, the first LED lights up at its lowest brightness, and with subsequent presses on the floor's pressure buttons, the brightness escalates.

Designed to visually represent the energy stored in a 2200µF capacitor, this display is grounded in the mathematical logic of the capacitor's charging sequence, as detailed in the calculations segment. It's timed impeccably for exhibition attendees to observe and interact with in real-time see video 3 of 2200µF capacitor charging.


[![Video 3](https://img.youtube.com/vi/_R7w6d5AlKY/0.jpg)](https://youtu.be/_R7w6d5AlKY)



The Capacitometer is mounted on laser-cut wood, with each of its 58 LEDs fitting snugly into a 2mm-edged hole,  See figure 22 below. A transparent acrylic layer, fashioned using laser technology, encases the device. The meter's scale spans from 0 to 730mC, indicative of the capacitor's charge, adjusted from 726mC for clarity and ease of understanding.
To ensure a harmonious visual presentation, the Capacitometer's stand has been crafted to echo the aesthetic of the HarvestWalk tile.


![Figure 22 Display the HarvestWalk Tile with the Capacitometer in the Exhibition](https://raw.githubusercontent.com/Gil-ADDA/Piezoelectric-Energy-Generation-HarvestWalk/ad374ace69ed69d8ef3663eaa5316ba4c4104757/Project%20Figures%20Tables%20and%20Diagram/Figure%2022%20Display%20the%20HarvestWalk%20Tile%20with%20the%20Capacitometer%20in%20the%20Exhibition.png)

 

 
** 11. Results **
11.1 Proof of Concept
As illustrated in Figure 4 see below the block diagram, the operational flow of the piezoelectric energy harvesting system is as follows:
Initiation: A step on the piezoelectric tile generates mechanical pressure, acting as the system's primary input.
Voltage Generation: This pressure deforms the piezoelectric discs, producing an AC voltage.
Voltage Management with LTC-3588-1: The AC voltage is channelled to the LTC-3588-1 chip for processing.
Input Capacitor Charging: A 10 µF capacitor receives and stabilises the AC voltage before it undergoes conversion.
Energy Storage: The LTC-3588-1 chip converts the AC voltage, directing it to an output capacitor.
Visual Output: The accumulated energy powers an LED diode, visually representing the successful energy conversion.
This sequence underscores the system's capability to transform mechanical stimuli into usable electrical energy, exemplified by the LED's illumination. For a practical demonstration of the system in action, please refer to the accompanying video 4.
[![Video 4](https://img.youtube.com/vi/eATSxM-Sl1c/0.jpg)](https://youtu.be/eATSxM-Sl1c)

 ![Diagram 4 HarvestWalk Scheme of Proof of Concept](https://raw.githubusercontent.com/Gil-ADDA/Piezoelectric-Energy-Generation-HarvestWalk/ad374ace69ed69d8ef3663eaa5316ba4c4104757/Project%20Figures%20Tables%20and%20Diagram/Diagram%204%20HarvestWalk%20Scheme%20of%20Proof%20of%20Concept.png)




** 12. Discussion**
The research has demonstrated the foundational viability of utilising piezoelectric tiles to harvest energy from footsteps to power IoT devices indoors. However, my study did not conclusively prove the capability to power IoT devices, but I was successful in illuminating an LED diode as detailed in the Results section under Proof of Concept. Nonetheless, the literature review suggests that it is indeed possible to achieve this. There are several aspects that could be enhanced to improve the efficiency and performance of the system.

Firstly, to achieve greater energy density, it is advisable to place piezoelectric discs over larger floor areas. The current prototype was restricted to 100 discs in a relatively compact form. Expanding the coverage would generate more cumulative energy from footsteps.

Secondly, the tile design could be optimised to allow for more deflection. Adopting a concave shape, as presented in the research "Powering Lights with Piezoelectric Energy-Harvesting Floors" in the chapter "Upgraded energy-harvesting devices for stairs", would permit more mechanical strain and deformation, thereby increasing energy output(Puscasu et al., 2018). It would also be beneficial to invest in piezoelectric materials that are specifically shaped like tiles and have a higher density of the crystal material. These specialised tiles would maximise the piezoelectric effect when subjected to downward forces from footsteps.

There is significant room for improvement in the electrical circuitry. Enhancements in the design can lead to better energy harvesting and storage. As the capacitance value increases, it becomes more challenging to charge the capacitor fully, which should be taken into consideration. Furthermore, the tile design can be further refined to maximise deflection. Incorporating temperature sensors and transmitting data via Bluetooth can also be optimised. Using more energy-efficient microprocessors would contribute to the overall efficiency of the system.

The experiments conducted have focused on evaluating the fundamental energy harvesting capabilities of the piezoelectric tile prototype. However, previous projects have successfully harvested energy to power sensors, indicating the feasibility of energising functional sensing systems with real-world applicability using piezoelectric tiles.



**13. Conclusions**
This research project has provided valuable insights into the potential of piezoelectric technology for indoor energy harvesting to operate IoT devices. The functioning prototype developed has established the fundamental feasibility of the approach. While current performance is modest, there are multiple avenues to markedly enhance the energy outputs by optimising the piezoelectric tile design and electrical system. With sufficient improvements, the concept could provide a practical sustainable energy solution for low-power smart building applications. The research contributes to knowledge in this emerging application domain and serves as a foundation for additional development. Considerable scope exists for subsequent projects to build on the groundwork established here and implement more sophisticated, higher performance systems. Piezoelectric energy harvesting from human motion offers an exciting paradigm for cleaner, maintenance-free energy to supplement battery usage for indoor electronics and wireless sensor networks.




**References **
Analog Devices, n.d. Technical Documentation Data Sheets. Available at: https://www.analog.com/media/en/technical-documentation/data-sheets/35881fc.pdf [Accessed 2 June 2023].

Arduino. (n.d.) UNO WiFi Rev2. Arduino. Available at: https://docs.arduino.cc/hardware/uno-wifi-rev2 (Accessed: 5 July 2023)

Ching, W.A., Geotina, M.J., Gora, N.S., Sucayre, R.J., Santiago, R.V.M. and Martinez, J.M., 2018. Implementation of Piezoelectric Generator for Harvesting Energy for Different Types of Staircases with Automatic Switching Mechanism. 2018 IEEE 10th International Conference on Humanoid, Nanotechnology, Information Technology, Communication and Control, Environment and Management (HNICEM). IEEE, Baguio City, Philippines, pp. 1–6

Components 101. (2020). How Does a Piezoelectric Generator Work? – Types and Characteristics. https://components101.com/articles/how-does-a-piezoelectric-generator-works-types-and-characteristics [Accessed 26 June 2023].

Covaci, C., Gontean, A., 2019. Energy harvesting with piezoelectric materials for IoT – Review. ITM Web Conf. 29, 03010. https://doi.org/10.1051/itmconf/20192903010 [Accessed 28 May 2023].

Covaci, C., Gontean, A., 2021. Piezoelectric Energy Harvesting using SSHI Technique, in: 2021 IEEE 27th International Symposium for Design and Technology in Electronic Packaging (SIITME). Presented at the 2021 IEEE 27th International Symposium for Design and Technology in Electronic Packaging (SIITME), IEEE, Timisoara, Romania, pp. 9–12. https://doi.org/10.1109/SIITME53254.2021.9663643

De Fazio, R., Perrone, E., Velázquez, R., De Vittorio, M., Visconti, P., 2021. Development of a Self-Powered Piezo-Resistive Smart Insole Equipped with Low-Power BLE Connectivity for Remote Gait Monitoring. Sensors 21, 4539. https://doi.org/10.3390/s21134539

Godard, N., Allirol, L., Latour, A., Glinsek, S., Gérard, M., Polesel, J., Domingues Dos Santos, F., Defay, E., 2020. 1-mW Vibration Energy Harvester Based on a Cantilever with Printed Polymer Multilayers. Cell Reports Physical Science 1, 100068. https://doi.org/10.1016/j.xcrp.2020.100068

Hudson-Smith, A. (2022) 'Open Weather Map NeoPixel Barometer – Open Gauges', UCL Connected Environments. Available at: https://connected-environments.org/blog/owmbarometer/ [Accessed 2 June 2023].

Hwang, S.J., Jung, H.J., Kim, J.H., Ahn, J.H., Song, D., Song, Y., Lee, H.L., Moon, S.P., Park, H., Sung, T.H., 2015. Designing and manufacturing a piezoelectric tile for harvesting energy from footsteps. Current Applied Physics 15, 669–674. https://doi.org/10.1016/j.cap.2015.02.009 [Accessed 28 May 2023].

Jawahar, M., Gruteser, M. and Howard, R., 2021. Kicking Yourself Awake: Towards self-powering mats for room-level localization and occupancy detection. Proceedings of the 22nd International Workshop on Mobile Computing Systems and Applications. ACM, Virtual United Kingdom, pp. 126–132.

Kim, K.-B., Cho, J.Y., Jabbar, H., Ahn, J.H., Hong, S.D., Woo, S.B., Sung, T.H., 2018. Optimized composite piezoelectric energy harvesting floor tile for smart home energy management. Energy Conversion and Management 171, 31–37. https://doi.org/10.1016/j.enconman.2018.05.031

Li, X., Strezov, V., 2014. Modelling piezoelectric energy harvesting potential in an educational building. Energy Conversion and Management 85, 435–442. https://doi.org/10.1016/j.enconman.2014.05.096 [Accessed 2 June 2023].

McDonald, K. (2008). DIY Force Sensitive Resistor (FSR). Instructables. Retrieved July 10, 2023, from https://www.instructables.com/DIY-Force-Sensitive-Resistor-FSR/

Pattipaka, S., Bae, Y.M., Jeong, C.K., Park, K.-I., Hwang, G.-T., 2022. Perovskite Piezoelectric-Based Flexible Energy Harvesters for Self-Powered Implantable and Wearable IoT Devices. Sensors 22, 9506. https://doi.org/10.3390/s22239506 [Accessed 2 June 2023].

Paul, P.J., Tutu, R.S.D., Richards, W.K., Jerome, V.M., 2015. Project power shoe: Piezoelectric wireless power transfer — A mobile charging technique, in: 2015 IEEE Global Humanitarian Technology Conference (GHTC). Presented at the 2015 IEEE Global Humanitarian Technology Conference (GHTC), IEEE, Seattle, WA, USA, pp. 334–339. https://doi.org/10.1109/GHTC.2015.7343993 [Accessed 2 June 2023].

Pavegen. (2022). What Can Pavegen Power. Available at: https://www.pavegen.com/what-can-pavegen-power [Accessed 20 May 2023]

Shanmugam, S., Selvaraj, V., Kasirajan, R., Sivakumar, H., Kandasamy, K., 2020. Household Energy Conservation Using Piezoelectric Tiles and solar Tracker. IOP Conf. Ser.: Mater. Sci. Eng. 955, 012071. https://doi.org/10.1088/1757-899X/955/1/012071

Sharpes, N., Vučković, D., Priya, S., 2016. Floor Tile Energy Harvester for Self-Powered Wireless Occupancy Sensing. Energy Harvesting and Systems 3, 43–60. https://doi.org/10.1515/ehs-2014-0009 [Accessed 10 June 2023].

Sharma, S., Kiran, R., Azad, P., Vaish, R., 2022. A review of piezoelectric energy harvesting tiles: Available designs and future perspective. Energy Conversion and Management 254, 115272. https://doi.org/10.1016/j.enconman.2022.115272

Shreeshayana, R., Raghavendra, L. & Gudur, M.V., 2017. Piezoelectric Energy Harvesting using PZT in Floor Tile Design. International Journal of Advanced Research in Electrical, Electronics and Instrumentation Engineering, 6(12), pp.8872. DOI:10.15662/IJAREEIE.2017.0612018.

Sodano, H. A., Inman, D. J., & Park, G. (2005). Comparison of Piezoelectric Energy Harvesting Devices for Recharging Batteries. Sage Journals, pages 16(10). doi:10.1177/1045389X05056681 [Accessed 20 June 2023]

Solban, M.M. and Moussa, R.R., 2021. Investigating the potential of using human movements in energy harvesting by installing piezoelectric tiles in Egyptian public facilities. Journal of Engineering Research, 9. Available at: https://doi.org/10.36909/jer.9517 [Accessed 2 June 2023].

Woodford, C., 2009. Piezoelectricity - How does it work? | What is it used for? [WWW Document]. Explain that Stuff. URL http://www.explainthatstuff.com/piezoelectricity.html (Accessed 6.26.23).
