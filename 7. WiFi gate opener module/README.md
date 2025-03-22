Design and implementation of a WiFi module for opening the entrance gate. The result was to be a module that can be connected (and integrated) into the control unit of gate drives from various manufacturers. 
The module should be able to connect to a WiFi network at a maximum distance of 30 meters, and the gate should be controlled from anywhere in the world.

The requirements for the module were therefore defined as follows:
  - Small dimensions, approximately 50x50x30 mm
  - Power supply voltage 12/24 V
  - 2x NO relay output, 2x input 12/24 V
  - Connection to a WiFi network with a maximum distance of 30 meters
  - Android/iOS application for hardware control

To meet the requirements mentioned above, an analysis of available hardware was done, focusing on size, connectivity, and the ability to implement software. The hardware used was the ESP32-WROOM-02U device, which allows an external WiFi antenna and has enough processing power. 
The final hardware was designed on a dual-layer PCB, which included not only the ESP32 section but also the power supply section and the part for connecting inputs and outputs.

For the software, the open-source Supla software was used, which is made for IoT applications. The developers of Supla software created an online configurator to allow using only the parts of the software that the hardware supports. 
After registration, Supla provides an online server that lets you control the hardware and monitor the status of input pins from anywhere in the world.

![alpus_1](https://github.com/user-attachments/assets/65e1ddfb-4282-45d8-ac98-fac051ec92a4)
![alpus_2](https://github.com/user-attachments/assets/fa3fb4f2-f1ca-48d3-933d-ced56202a65c)
![alpus_3](https://github.com/user-attachments/assets/8501b569-3c04-4d36-a5d2-194b71c42600)
![alpus_4](https://github.com/user-attachments/assets/91cfb288-b150-4bde-8097-d8fefd3f1bd0)
![alpus_5](https://github.com/user-attachments/assets/5021e9d9-8d6e-423c-b332-3b2c84d395b5)

Photos of real hardware:

![alpus_6](https://github.com/user-attachments/assets/fadc9470-725d-4a27-b396-a0c33d4c53ae)
![alpus_7](https://github.com/user-attachments/assets/bb273aa9-f0b7-4ee9-9215-4aba458d5b5f)
![alpus_8](https://github.com/user-attachments/assets/f0b25b45-2681-4f75-8160-a8f28a1a950f)
![alpus_9](https://github.com/user-attachments/assets/48ed8c32-e392-4822-a97a-4debc9c79c76)
