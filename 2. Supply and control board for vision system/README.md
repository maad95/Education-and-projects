Development of supply and control board for vision (observation) system consist of three elements - block TV/day camera, thermal camera, LRF. Development of HW part with an emphasis on modularity, scalability, limited dimensions and with regard to the best EMC/EMI parameters.
Supply and control board connected together by vibration proof connectors. 

Requirements for supply board:
- DC/DC step-down from 24V (±3V) to 12V@5A and 5V@5A
- provides power supply for control board and all components of system 
- limited PCB dimensions
- possibility of installing a heatsing on the supply board

![supply_board](https://github.com/user-attachments/assets/638eda63-1286-4ff1-b253-36ccaa140767)
![supply_board_top](https://github.com/user-attachments/assets/6f422747-83f7-4fc9-98b2-c563bd8c1193)
![supply_board_bottom](https://github.com/user-attachments/assets/3b475343-9cc9-441d-a43c-36719a00d9a0)

Requirements for control board:
- four communication interfaces, three for internal components of observation system, one for communication with external devices/systems
- internal componenets - block TV/day camera (UART), thermal camera (RS232), LRF (UART)
- external system communication by RS422
- same dimensions as supply board
- temperature sensing and control of fan for cooling

Control board is based on Atmel AVR MCU. Code is written in C language with a strong use of interruptions for communication protocols with handshaking/CRC. Temperature is sensing by NTC thermistor.

![control_board_AVR](https://github.com/user-attachments/assets/3c4a94af-e19f-490f-a5ca-ce025d9ac13a)
![control_board_AVR_top](https://github.com/user-attachments/assets/567f2ead-0484-4cab-8064-70ea21883e7f)
![control_board_AVR_bottom](https://github.com/user-attachments/assets/efc414bc-eff8-440d-afac-51adc3a302bd)

A cooler and a fan holder were also designed for the system. Cooling process started in case the temperature rose above the certain value.
These boards together form a modular equipment that meets the required parameters of power supply for system elements , modularity and installation dimensions.

![supply+control+heatsink](https://github.com/user-attachments/assets/5427db4a-5303-4c35-aaae-5393e62e0079)
![supply+control+heatsink_right](https://github.com/user-attachments/assets/58381f3c-c5c5-4607-8e69-f10766f51960)
![supply+control+heatsink2](https://github.com/user-attachments/assets/ab126e3e-7556-4c0c-bca7-2d93c98596db)
