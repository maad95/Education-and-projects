Development of supply and control board for vision (observation) system consist of three elements - block TV/day camera, thermal camera, LRF. Development of HW part with an emphasis on modularity, scalability and limited dimensions.
Supply and control board connected together by vibration proof connectors. 

Requirements for supply board:
- DC/DC step-down from 24V (±3V) to 12V@5A and 5V@5A
- provides supply for control board and all internal components of system 
- limited PCB dimensions
- possibility of installing a heatsing on the supply board

![supply_board](https://github.com/user-attachments/assets/638eda63-1286-4ff1-b253-36ccaa140767)
![supply_board_top](https://github.com/user-attachments/assets/6f422747-83f7-4fc9-98b2-c563bd8c1193)
![supply_board_bottom](https://github.com/user-attachments/assets/3b475343-9cc9-441d-a43c-36719a00d9a0)


Requirements for control board:
- four communication interfaces, three for internal components of observation system, one for communication with external devices/systems
- internal componenets - block TV/day camera (UART), thermal camera (RS232), LRF (UART)
- external system communication by RS422
