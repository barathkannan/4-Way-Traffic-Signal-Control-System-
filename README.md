# 4-Way-Traffic-Signal-Control-System
4-Way Traffic Signal Control System Using Tia Portal

# Project Description
**This project simulates a fully automated 4-way traffic light control system using a PLC with HMI, The system manages traffic flow at an intersection by coordinating the signals (Red, Yellow, Green) for four directions in a timed sequence. The program ensures that only one direction gets the green signal at a time while the others remain red, the HMI is used to monitor and control the system in real time, offering an interactive interface for operators.**

## Built with
- **Software**: TIA Portal
- **PCL**: S7-1212
- **HMI**: TP Comfort 700
- **Programming Language**: LAD (Ladder Diagram)
  

# Working algorithm 
**Using TON for delay 15sec for Green and 5sec for Yellow**


![Image](https://github.com/user-attachments/assets/63726963-f2e7-4a02-8840-ba74bf8453e9)


# Key Features

- **Timed signal control for all four directions with safe transition delays**

* **Only one direction gets the green signal at a time (avoids conflict)**

+ **HMI display showing current signal status for each direction**



# Configure PLC and HMI
**Connecting both via Ethernet**

![Image](https://github.com/user-attachments/assets/ab4a4df2-8cb2-4d64-915f-635deaeae524)


## Programming in LAD Diagram

![Image](https://github.com/user-attachments/assets/8f8240f8-ebec-44a8-860a-a19d13920ba5)

**Using Tag Table to config program**

![Image](https://github.com/user-attachments/assets/254d4250-8700-41a7-bc69-90e4e05dda35)

# HMI Configuratiion

**Used Start and Stop buttons to control the traffic signal operation. Configured signal lights through HMI for manual adjustments and real-time monitoring.**

![Image](https://github.com/user-attachments/assets/81189eb2-d2c7-4590-a480-454a77bb5af6)

**Mapping signal lights**

![Image](https://github.com/user-attachments/assets/3261643e-48cc-4e8e-be3a-c1e6d8b48704)



# Simulating HMI and Monitoring 

**Started HMI simulation and switched to online mode in TIA Portal to monitor and verify functions in the LAD diagram in real time.**

![Image](https://github.com/user-attachments/assets/c1ae9652-5f01-436f-b23f-7b2bf3a4ff3a)


**Monitoring the LAD diagram in online mode to observe real-time execution of logic and verify system behavior.**

![Image](https://github.com/user-attachments/assets/3f9f803b-4598-4646-b92c-8f05a00b1208)


## Conclusion

**This project provided a practical understanding of traffic signal automation using PLC and HMI. It strengthened my skills in ladder logic programming, timing control, and real-time monitoring. Integrating Start/Stop functions and manual signal editing through HMI improved system flexibility and safety. Overall, the project reinforced key concepts in industrial automation and control system design.**


  


