<h2 align="center">Müslüm Can Kandamar</h2>

<p align="center">
  <b>Mechatronics Engineer · Embedded Software · Motor Control · Model-Based Design</b><br>
  İzmir, Türkiye
</p>

---

### About

Mechatronics engineer working where software meets hardware, from a Simulink plant model to C++ running in a 20 kHz interrupt on a real motor.

- **Embedded software:** STM32 firmware in C and C++ for FOC motor drives, CANopen (CiA 402), USB, CAN tooling, bootloaders and secure boot.
- **Model-Based Design:** control systems designed in MATLAB/Simulink and Simscape, verified in MIL/SIL and deployed with Embedded Coder.
- **Electric vehicles:** former electrical department lead of IKC Racing (Formula Student), where I started the team's first electric vehicle program.
- **Education:** B.Sc. in Mechatronics Engineering, İzmir Kâtip Çelebi University.

---

### Featured Projects

| Project | Description | Stack |
|---|---|---|
| [**stm32g4-foc-motor-drive**](https://github.com/MCanKandamar/stm32g4-foc-motor-drive) | BLDC/PMSM drive firmware on STM32G473: 20 kHz FOC with Hall or sensorless sliding-mode observer angle, a CANopen CiA 402 node, fault protection, unit tests, CI and hardware-in-the-loop tests. | C++20 · FreeRTOS · CANopenNode · GoogleTest |
| [**FOC-ModelBasedDesign-STM32G4**](https://github.com/MCanKandamar/FOC-ModelBasedDesign-STM32G4) | Graduation project: cascaded FOC of an EV-scale PMSM modeled in Simulink/Simscape, verified in MIL/SIL and generated with Embedded Coder for an STM32G474RE bench setup. | MATLAB · Simulink · Simscape · Embedded Coder |
| [**FourBar-RealTimeControl-ModelBasedDesign**](https://github.com/MCanKandamar/FourBar-RealTimeControl-ModelBasedDesign) | Real-time PID position and velocity control of a four-bar mechanism, deployed to Arduino and tuned live from a MATLAB app over a binary UART protocol. | Simulink · Arduino · App Designer |
| **stm32-slcan** *(private repository)* | USB-to-CAN adapter firmware for STM32F072 with the LAWICEL SLCAN command set over USB CDC, tested with SavvyCAN, python-can and Linux SocketCAN. | C · STM32 · CAN · USB |
| [**imu-tilt-kalman**](https://github.com/MCanKandamar/imu-tilt-kalman) | Two-state Kalman filter (tilt angle and gyro bias) in portable C++, to be tested in simulation, on recorded sensor data and on an STM32. **Early stage: the project has just started.** | C++17 · CMake · GoogleTest |

### Tools for AI Coding Agents

| Project | Description |
|---|---|
| [**agent-lite**](https://github.com/MCanKandamar/agent-lite) | A small Markdown and git based working system that keeps an AI agent's plan and progress in the repository, so a new session (Claude Code, Codex) can continue the work and recover interrupted steps. |
| [**context-guard**](https://github.com/MCanKandamar/context-guard) | A hook for Claude Code and Codex that reminds you when a long session should be compacted or restarted, and what to keep. |

---

### Highlights

- Reached the motor's maximum speed of **3,560 rpm** in both Hall and sensorless (SMO) modes on a custom STM32G473 FOC drive.
- Brought up all three STM32H5 secure boot paths (**STiRoT, OEMiROT, STiRoT + OEMuROT**) with signed, encrypted firmware updates over USB DFU.
- Started a Formula Student team's **first electric vehicle program** and coordinated its HV, LV, battery, embedded software and control subteams.
- Project lead of a **TÜBİTAK 2209-A** project on the design and manufacturing of a BMS for an electric race car.
- Co-author of *Industrial Battery Energy Storage Unit Investigations for Time-Dependent Experimental Characterization*, **IEEE ICECET 2025**, Paris. [DOI: 10.1109/ICECET63943.2025.11472377](https://doi.org/10.1109/ICECET63943.2025.11472377)

---

### Tech Stack

**Embedded**<br>
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++20-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![STM32](https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white)
![Arm](https://img.shields.io/badge/Arm%20Cortex--M-0091BD?style=flat-square&logo=arm&logoColor=white)
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-5A9E1E?style=flat-square)
![ThreadX](https://img.shields.io/badge/ThreadX%20%2F%20USBX-0078D4?style=flat-square)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=flat-square&logo=arduino&logoColor=white)

**Protocols**<br>
![CAN](https://img.shields.io/badge/CAN%20%2F%20CANopen%20CiA%20402-555555?style=flat-square)
![USB](https://img.shields.io/badge/USB%20CDC%20%2F%20DFU-555555?style=flat-square)
![Serial](https://img.shields.io/badge/UART%20%C2%B7%20SPI%20%C2%B7%20I2C%20%C2%B7%20isoSPI-555555?style=flat-square)

**Model-Based Design & Control**<br>
![MATLAB](https://img.shields.io/badge/MATLAB-E16737?style=flat-square&logo=mathworks&logoColor=white)
![Simulink](https://img.shields.io/badge/Simulink-E16737?style=flat-square)
![Simscape](https://img.shields.io/badge/Simscape-E16737?style=flat-square)
![Stateflow](https://img.shields.io/badge/Stateflow-E16737?style=flat-square)
![Embedded Coder](https://img.shields.io/badge/Embedded%20Coder-E16737?style=flat-square)
![Control](https://img.shields.io/badge/FOC%20%C2%B7%20SVPWM%20%C2%B7%20SMO%20%C2%B7%20PID-6E40C9?style=flat-square)

**Hardware & Tools**<br>
![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white)
![GoogleTest](https://img.shields.io/badge/GoogleTest-4285F4?style=flat-square&logo=google&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Altium](https://img.shields.io/badge/Altium%20Designer-A5915F?style=flat-square&logo=altiumdesigner&logoColor=white)
![LabVIEW](https://img.shields.io/badge/LabVIEW-FFDB00?style=flat-square&logoColor=black)
![SolidWorks](https://img.shields.io/badge/SolidWorks-D71920?style=flat-square&logo=dassaultsystemes&logoColor=white)

---

### Languages

Turkish (native) · English (professional working proficiency) · German (elementary)
