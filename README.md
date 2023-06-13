# Piezoelectric-Energy-Generation-HarvestWalk-For-IOT 
The primary goal of this repository is to explore the potential of piezoelectricity for energy generation and develop sustainable solutions for IOT devices. By openly sharing my research findings, experimental setups, component evaluations, and design considerations, I hope to inspire discussions and invite valuable insights from the community


Be involved in this repository - researchers, engineers, and enthusiasts interested in piezoelectric energy **are all welcome!** Share your ideas, feedback, and more to help this project reach its full potential. With everyone's help, we can work towards a more sustainable future. No matter your experience, your input is invaluable - so please reach out and contribute via opening issues, email, or any other suggestions!

the piezoelectric tiles can turn steps into energy. Over a year, this energy could replace a portion of electricity usually pulled from the grid. This means less reliance on traditional power sources, which often produce CO2, a greenhouse gas. Plus, it saves money on electricity bills. 
Besides, these tiles can potentially offer a clean, wire-free solution for powering IoT devices. Imagine a city where foot traffic in public spaces like parks, subway stations, or sidewalks generates power for public IoT devices. 

# Problem statment 
With the proliferation of IoT devices in indoor environments like homes and offices, providing a sustainable, wireless power source for these devices is a significant challenge. This is particularly relevant for low-power devices such as temperature or humidity sensors and smart switches, which are frequently used in these settings. The problem is compounded by the need to reduce wire clutter and improve aesthetics. This project aims to investigate whether a piezoelectric tile, harvesting energy from regular foot traffic or other mechanical stimuli in these environments, could generate sufficient power to operate these sensors and switches. A key part of this investigation will be to accurately measure the amount of electrical energy each tile generates. 

## Contact Details
[<img src="https://img.icons8.com/color/48/000000/gmail.png"/>](mailto:giloo1047@gmail.com)
[<img src="https://img.icons8.com/color/48/000000/linkedin.png"/>](https://www.linkedin.com/in/gil-adda-16385510b/)

# Reserch field
The reserch filed going to be around urban renewable energy and pizoelectric 

## Potential Component List

The "potential Component List" section contains a comprehensive list of components that will be investigated and considered for piezoelectric energy generation research. The list: 
- 5 X pizo (piezoelectric materials - what is the best for generate energy?) (Diaphragm)

- Bridge rectifier ( which one is the most suitable?) 

- Energy storage systems - dose Capacitor is the best for that project? 

- Capasitor Microfarad capacitor 10 MF  (max 50 volts ) (for charging ) (what is the speed of charging and why I should consider that ? ) 
how much Microfarad (µF) do i need for that project? 




- Diode (note the energy cost for that is 0.6-0.7 volts)  OR Germanium diode (energy cost of 0.3)

By documenting the planned components, we aim to explore the available options, evaluate their suitability for our research objectives, and make informed decisions. This section will be continuously updated as we research and assess different components, providing transparency and facilitating collaboration with the community


# Design of the tile
List of materials :

Rubber tile: The choice of material is essential here. Rubber is chosen because it is durable, flexible, and resilient, for frequently walking.

Rubber ball: This will be placed in the middle of the tile, acting as the central point of contact. The ball should be small enough to fit comfortably in the space between the two halves of the tile, but large enough to make contact with both piezoelectric sensors when pressure is applied to the tile.
# patterns and thoughts of how to create the piezoelectric device


# Thoughts of which devices to power 

1. lights 
2. microcontrollers 
3. Occupancy Sensors
4. green communication (node)
5. Smart switches


# potential ways to visualize the results: 

Visual Representations:  The more steps, the brighter the light.

Time-based Comparisons: how much energy would be generated over time.

# Inspiration Videos and Articles

1. https://www.youtube.com/watch?v=dO8zsgbunvY - Piezoelectric Effect - Using Crystals to Generate Electricity
2. https://www.youtube.com/watch?v=RiRyzLl4Y8U - Full Wave Bridge Rectifier + Capacitor filters + half wave rectifier (the engineering mindset)



(https://reader.elsevier.com/reader/sd/pii/S0196890422000681?token=AFD5F7CA93BB9FAA56042AC6F2865C62F7A5FC66C200C1C4D9B9C6044E4D53B57DBC336F071ADACD4F7C774C14C267E5&originRegion=eu-west-1&originCreation=20230511141830
A review of piezoelectric energy harvesting tiles)

## The decision making process
- making tile of piezoelectric for harvesting energy 
- create the circuit
- material of the tile
- conductive materials
- what  to measure ?
- how to display the data after deploy the tile

# process of creation 
-  checking the current flow of the bridge rectifier

 [![ 17/5checking the current flow](https://img.youtube.com/vi/git2ZRKCuz4/0.jpg)](https://youtube.com/shorts/git2ZRKCuz4)
 
- checking the charge of supercapacitor

 [![ 17/5checking the charge of supercapacitor](https://img.youtube.com/vi/cgkGJ2SmKRU/0.jpg)](https://youtube.com/shorts/cgkGJ2SmKRU)
 
- Different way of creating the circuit : Copper foil underneath for the negative side and above for the positive side. Moreover the piezoelectric cover with tape to prevent from that to brake.
![Circuit with Copper Foil](https://github.com/Gil-ADDA/Piezoelectric-Energy-Generation-HarvestWalk/blob/91495337293ec5821d29b22b9583bb38f568e1e7/images/circute%20with%20cooper%20foil%20for%20negative%20and%20positive%20Large.jpeg)




# Second Prototype
In the second prototype, I attached the copper foil and piezoelectric component to a cardboard surface using a clear adhesive. This method ensured that the circuit components remained securely in place.

To achieve this, I carefully adhered the copper foil, both the negative and positive sides, along with the piezoelectric component onto the cardboard. The copper foil acted as the conductive material for the circuit, while the clear adhesive provided a strong bond between the components and the cardboard surface.

By affixing the circuit elements to the cardboard, I created a stable and functional prototype that maintained the desired circuit arrangement.

In the video at 0:36, a captivating demonstration was shown, illustrating the charging process of 470 microfarads (μF), 16-volt (V) capacitor
The video showcases the charging process of a 470 microfarads (μF) capacitor. By utilizing the impact of footsteps on a tile surface, an estimated current of approximately 0.5 milliamperes (mA) or 0.0005 Amperes (A) is directed into the capacitor. 
**Using the formula Q = C × V, where Q represents the charge, C represents the capacitance, and V denotes the voltage across the capacitor,** the calculated charge on the capacitor is approximately 470 × 10^(-6) Coulombs (C), or 470 micro coulombs (μC). 
The specific voltage value is not provided, but with the known capacitance and the applied voltage, it is possible to estimate the charge accumulation. The demonstration illustrates the utilization of mechanical energy from footsteps to generate an electrical charge and charge the capacitor.

## checking the charge of supercapacitor with the second prototype 
 [![ 6/6 checking the charge of supercapacitor with the new circute ](https://img.youtube.com/vi/lCWuk8zGKjg/0.jpg)](https://youtu.be/lCWuk8zGKjg)
 
![Circuit with Copper Foil](https://github.com/Gil-ADDA/Piezoelectric-Energy-Generation-HarvestWalk/blob/6ac9517e8cfcaad6a790751ce78773cfdc16aff2/images/The%20circuit%20of%20the%20second%20prototype.jpeg)
## The layers
|------------------------|
|   Copper Foil          |  <- Positive Side
|------------------------|
|   Clear Stick Wrap     |
|------------------------|
|   Piezo Electric       |
|------------------------|
|   Negative Copper Foil |  
|------------------------|
|   Cardboard            |
|------------------------|
