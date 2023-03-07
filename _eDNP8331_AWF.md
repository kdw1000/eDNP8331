
## 1. Schematic

The first step on the path to an eDNP/8331-based embedded system solution is to create a new Altium Designer project and import the eDNP/8331 CAD files as a root sheet. Within the project, the eDNP/8331 Schematic Snippet is then placed on the Altium Designer workspace and wired to its own circuit functions. Unused eDNP/8331 pins remain unconnected. As external power supply, the eDNP/8331 requires only 3.3 VDC. An external clock and reset signal is not required. For 24 VDC to 3.3 VDC power supply and the use of the eDNP/8331 standard interfaces, such as 10/100 Mbps Ethernet LAN, circuit diagram examples are included.

![Overview](https://ssv-comm.de/forum/bilder/8331_AWF_1.png)

## 2. Layout

After the schematic is completed and tested, a board layout for the PCB is created from the entire schematic. For this step the eDNP/8331 PCB Snippet is needed. This object can be placed as desired within the PCB space during the Altium Designer PCB design phase. When using the eDNP/8331 PCB snippet, some design rules have to be observed (e.g. some naming conventions, binding of PCB layers for power supply, connections to Ethernet LAN connector). The goal of the layout phase is an PCB CAD dataset from which a manufacturer can produce the desired PCBs.

![Overview](https://ssv-comm.de/forum/bilder/8331_AWF_2.jpg)

## 3. BoM and Production Data

![Overview](https://ssv-comm.de/forum/bilder/8331_AWF_3.jpg)

## 4. Prototyping

![Overview](https://ssv-comm.de/forum/bilder/8331_AWF_4.jpg)
