<p align="center">

</p>



<h2>Video Demonstration</h2>

- ### [YouTube: Day 2 Lab Connecting Devices](https://www.youtube.com/watch?v=JlkABUDyBZU)

<h2>Environments and Technologies Used</h2>

- Jeremy's IT Lab Youtube Channel
- Cisco Packet Tracer
  

  
<h2>Operating Systems Used </h2>

- Cisco IOS


<h2>Step-by-Step</h2>

<b>🟢 Part 1 — Connect PCs and Server to Switches</b>

- Assume Auto MDI-X is disabled.

- Remember PCs transmit on pins 1,2 and receive on pins 3,6.

- Remember switches transmit on pins 3,6 and receive on pins 1,2.

- Use copper straight-through cables for PC and server connections.

- Select Copper Straight-Through.

- Connect PC1 FastEthernet0 → SW3 FastEthernet.

- Connect PC2 FastEthernet0 → SW4 FastEthernet.

- Connect PC3 FastEthernet0 → SW7 FastEthernet.

- Connect SRV1 FastEthernet0 → SW8 FastEthernet.

<b>🟢 Part 2 — Connect Switches Together</b>

- Remember devices of the same type require crossover cables.

- Select Copper Crossover.

- Connect SW3 → SW1.

- Connect SW1 → SW2.

- Connect SW4 → SW2.

- Connect SW7 → SW5.

- Connect SW5 → SW6.

- Connect SW8 → SW6.

<b>🟢 Part 3 — Connect Switches to Routers</b>

- Remember routers transmit on pins 1,2 and receive on pins 3,6 like PCs.

- Use copper straight-through cables.

- Select Copper Straight-Through.

- Connect SW1 → R2.

- Connect SW2 → R2.

- Connect SW5 → R4.

- Connect SW6 → R4.

<b>🟢 Part 4 — Connect Routers Together</b>

- Remember same device types use crossover if copper is used.

- Check distances before selecting cable type.

- Use Copper Crossover for short distances.

- Connect R2 → R1 with copper crossover (50 meters).

- Identify long-distance links.

- Use fiber optic for long distances.

- Choose single-mode fiber for very long links.

- Connect R1 → R3 with fiber (3 km).

- Choose multimode fiber for medium distances.

- Connect R3 → R4 with fiber (250 m).

<b>🟢 Part 5 — Finish</b>

- Verify all devices are connected.

- Check for link lights.

- Save the Packet Tracer file.

- Prepare for configuration labs.
