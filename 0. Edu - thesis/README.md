**B.Sc. - The use of digital filters in the control of a synchronous motor with permanent magnets** 

Developed parts: FOC for synchronous motor with permanent magnets, first order filter, second order filter, moving average and Kalman filter

  Power converter based on TMS320F28377:

![bc2](https://github.com/user-attachments/assets/8bece234-03f2-4914-8c40-ecbcf37a48a6)
![bc1](https://github.com/user-attachments/assets/654701bb-3bc1-4a38-ae3f-7f041be538bb)

Input and output waveforms of the second order filter for different smoothing factors:
  ![bc3](https://github.com/user-attachments/assets/78e77133-5282-4834-a4ea-64a5f4c5d516)

Actual speed (blue) and speed from Kalman filter (red) of PMSM:
![bc4](https://github.com/user-attachments/assets/d817cbd0-1c85-414f-9f10-89d4b1e9f665)

**M.Sc. - Implementation of the EtherCAT communication bus in a modular converter for actuators** 

Developed parts: Simple HW for connection between EtherCat module and modular servo drive. SW for transfer data between EtherCat module (Based on Beckhoff IC + TI TMS320 DSP)

Modular servo drive:

  ![ing1](https://github.com/user-attachments/assets/62abd578-153c-491d-9981-cd9c10c14601)

EtherCAT module:
![ing2](https://github.com/user-attachments/assets/55a701a6-640e-46ed-a3d9-edbf53b88c6c)

  Schematic with SPI signals and designed interface:
![ing3](https://github.com/user-attachments/assets/4066e829-e543-4b31-8a32-e4d99e9d4c63)
![ing4](https://github.com/user-attachments/assets/27cadef5-9410-4987-a4e5-de20b98cf2a8)

Converter + module:
![ing5](https://github.com/user-attachments/assets/684ec1ad-5343-435e-8464-715e246b7b4a)

Master <-> Slave communication:
![ing6](https://github.com/user-attachments/assets/fbca4978-8b46-4790-aa10-ea89cdb821c8)


**Ph.D. - Control of power converters in multiport connection**

Developed parts: Design of planar transformer based on required parameters of multiport converter. SW for converter for power control and communication between other ports. (Based on TI TMS 320)

Planar transformer from ANSYS simulation:

![phd3](https://github.com/user-attachments/assets/f080df6d-2d0b-48fe-9e1b-8444028f5dc9)

Real planar transformer: 
![phd4](https://github.com/user-attachments/assets/525c7adb-ac64-4810-ada6-7d81eb948b0e)

N port multiport converter:
![phd5](https://github.com/user-attachments/assets/f3e72597-7acc-4502-ac0b-87e851ca8cbd)

Real multiport converter with three ports:
![phd6](https://github.com/user-attachments/assets/27335a9f-bc29-4f98-ab83-f2b06d1f6d07)

Waveforms (all currents) from three port converter, ip1 (port 1) and ip2 (port 2) as a supply currents, ip3 (port 3) as a sum of ip1 + ip2 and as load current:
![phd7](https://github.com/user-attachments/assets/0dc762cc-d6c9-4cb0-bedd-0f24fa90b085)






