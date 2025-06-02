# PLC_Simulation_PCB_Soldering
Simulation of SMD Soldering (IR Method) in CODESYS

This project simulates a simplified SMD (Surface-Mount Device) soldering line using the infrared (IR) reflow soldering method, implemented in CODESYS.
The simulation represents the key stages of an industrial soldering line.

The main objective was to demonstrate how a PLC might control the operation of:
- a roller conveyor system,
- an IR reflow oven controlled by PID controller,
- a testing zone,
- a 2-axis manipulaotr with pneumatic gripper, which places the product into appropriate container (OK box or NOK(scrap) box)

This project was mainly intended as a way to learn and practice PLC programming languages as part of a university course. At the same time, I wanted to challenge myself by creating a more complex and realistic automation scenario. I was inspired by real-world PCB manufacturing techniques, and aimed to reflect key steps of that process in my simulation. Although it took hours of research on how soldering is done, I managed to finish this project.

Additionally, I focused on developing software capable of handling errors, such as verifying whether the PCB product reached the designated zone and implementing timeouts to manage unexpected delays or faults.
To simulate the oven’s operation, I used discrete control equations to model its thermal behavior more accurately.
Moreover, I carried out the selection of electrical components and designed a simplified electrical diagram for the system.

![obraz](https://github.com/user-attachments/assets/50aeb005-cd5d-4593-87f2-c8b8804556fe)

![obraz](https://github.com/user-attachments/assets/7e273e8b-49fc-45a1-a81c-72cdba43cda4)
