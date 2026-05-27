# USB-Hub
This is a USB hub made from the tutorial on Hack Club Macondo.

You would use it by plugging the upstream port into your computer and plugging the downstream ports into whatever you want to power or connect to your computer.

I made this so I could get better experience making PCBs and designing things in CAD. I also just wanted a USB Hub and what's a better way to get one than by making it yourself?

## 3d Printed Case
The case I made has a top and a bottom to allow the PCB to be inserted for assembly, along with variables to easily edit dimensions of the case.

Top:
<img width="1205" height="530" alt="USB hub top" src="https://github.com/user-attachments/assets/053ff3bc-ad3a-46a6-9445-50e940a79390" />

Bottom:
<img width="1205" height="667" alt="USB hub bottom" src="https://github.com/user-attachments/assets/e3e6170d-daa8-4eac-9f91-ceed086c5399" />

I made it using Onshape.

## PCB
I made the PCB using EasyEda. It has a USB C port for the upstream port and 3 USB A ports with 1 USB C port for the downstream ports. It has the tab sticking out of it so it can rotate into the case for assembly.

Schematic:
<img width="1272" height="896" alt="USB hub schematic" src="https://github.com/user-attachments/assets/6328b9a0-7ae1-4099-935d-9fa20ff7f9ba" />

PCB:
<img width="1799" height="871" alt="USB hub pcb" src="https://github.com/user-attachments/assets/55159ee8-96ba-4f31-bba3-efe0d8a4e03e" />

3d Model:
<img width="1271" height="579" alt="USB hub pcb model" src="https://github.com/user-attachments/assets/7732a143-6f86-441f-b639-788ecc05a376" />

## BOM
This should be all of the parts needed to make the USB Hub:
- M2x5mm Hex Socket Screws
- M3xL3xOD3 Brass Heatset Inserts
- 3d printed case, top and bottom
- Assembled PCB, with resistors, capacitors, and USB ports

## Build Instructions
To make this USB Hub, these are the steps you need to take:
1. Order all of the parts from the BOM, getting the PCB assembled by JLCPCB.
2. Insert the heatset inserts into the spots for them on the case, making sure not to insert them too far.
3. Put the PCB into the case. You should be able to just rotate it in.
4. Screw the PCB onto the case (don't overtighten) and screw the lid onto the case.
