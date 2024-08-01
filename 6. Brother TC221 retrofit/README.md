Development of both, hardware (electrical) and software part for retrofit old Brother TC221. This center is originally marked as "tapping", but in the result should be fully usable as milling center. 
The initial idea was to replace only the control system (old Brother system) with respect the old servomotors and servo drives. 

First picture of center at home:
![IMG-20221107-WA0000](https://github.com/user-attachments/assets/da44bedb-ecaa-45ca-a4a1-afe26e9db1b9)

After center come home, the sequence of works was chosen as follows:
  - analysis of old system components connections, use cases, owner's requirements, etc...
  - design of new system architecture, select new control system and also select hardware for connection with hardware layer
  - support with design of new operator panel (touchscreen switches, physically switches, knobs for set speed, etc....)

During my analysis of system, my friend completely disassembled and overhauled the mechanical part of the machine. He thought it would be easy, but it turns out the original ball guides and ball screws for axis are in bad shape. 
Therefore, there was a long wait for new ball guides and ball screws... (approx. 3 months)

Half disassembled TC221 with new ball guides and new ball screws:
![IMG-20230904-WA0000](https://github.com/user-attachments/assets/9a8be5c7-bccd-4e92-b42c-012506c3f2d0)

After many long sleepless nights as a new control system was selected LinuxCNC. LinuxCNC is composed from four main components: motion controller, IO controller, task executor and GUI.
As a hardware layer of system was selected FPGA cards from MESA which are easily configurable and there is a big support for them on LinuxCNC forum. 
LinuxCNC components and FPGA cards (physical hardware) are connected by HAL (hardware abstraction layer) configuration file.
New system HW (electrical) and SW part composed of:
  - HP EliteDesk 800, i3, 8GB RAM, SSD with installed and configured LinuxCNC [part of operator panel]
  - MESA 7i92TM (ethernet interface) + 7i77 (analog servo drives) + 7i37 (for tool changer) + 7iA0 (for all other IOs) [part of machine]
  - Operator panel (all required switches and knobs + touchscreen + keyboard with touchpad)
  - MPG jog pendant [connected to operator panel]
  - Drives for all axis were left original ((not for long time...))

After axis regulator tunning and first test of axis feed rate, 



Retrofit old Brother TC221 three axis milling center with 10 pockets in tool changer. Full HW and SW design (LinuxCNC + MESA cards, Digitax M751 drives for all axis, design of PCB for old motor sensor emulation, operator panel with buttons, etc...)
