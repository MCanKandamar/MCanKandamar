<h1 align="center">Hi, I'm Müslüm Can Kandamar 👋</h1>

<p align="center">
  <b>Mechatronics Engineer · Embedded Software · Motor Control · Model-Based Design</b><br>
  STM32 firmware in C/C++ · FOC drives · CANopen · Secure boot · MATLAB/Simulink · EV battery systems
</p>

<p align="center">
  📍 İzmir, Türkiye &nbsp;·&nbsp; 🎓 B.Sc. Mechatronics Engineering, İzmir Kâtip Çelebi University &nbsp;·&nbsp; 🏎️ ex-Electrical Lead, IKC Racing (Formula Student EV)
</p>

---

### 🔧 About me

I work where software meets hardware: from a Simulink plant model to C++ running in a 20 kHz interrupt on a real motor.

- ⚙️ **Embedded Software Intern @ Enko Kontrol Sistemleri**: FOC motor drive firmware in C++20 with CANopen (CiA 402), secure boot and firmware update on STM32H5 (STiRoT, OEMiROT/MCUboot), USB DFU bootloaders, USB-to-CAN tooling and boost converter control.
- 🧠 **Model-Based Design**: cascaded FOC, PID and battery estimators designed in Simulink/Simscape, verified in MIL/SIL, and deployed with Embedded Coder.
- 🔋 **Electric vehicles**: started IKC Racing's first EV program from scratch, defined its E/E architecture, sized a 432 V / 7.8 kWh pack and led the TÜBİTAK 2209-A BMS project.
- 🤖 **AI tooling on the side**: small, file-based tools that make AI coding agents easier to work with over long projects.

---

### 🚀 Featured projects

| Project | What it is | Stack |
|---|---|---|
| ⚡ [**stm32g4-foc-motor-drive**](https://github.com/MCanKandamar/stm32g4-foc-motor-drive) | BLDC/PMSM drive firmware: 20 kHz FOC with Hall or sensorless SMO + PLL angle, CANopen CiA 402 node, fault protection, live debugging with Scrutiny, unit tests, CI and HIL tests | C++20 · STM32G473 · FreeRTOS · CANopenNode · TinyUSB · GoogleTest · GitHub Actions |
| 🎛️ [**FOC-ModelBasedDesign-STM32G4**](https://github.com/MCanKandamar/FOC-ModelBasedDesign-STM32G4) | Graduation project: cascaded FOC of an EV-scale PMSM (EMRAX 208, 432 V pack) in Simulink/Simscape, then code-generated to an STM32G474RE bench with a live telemetry app | MATLAB · Simulink · Simscape · Embedded Coder · Stateflow · App Designer |
| 🚌 [**CANdamar**](https://github.com/MCanKandamar/CANdamar) | CAN bus analyzer for slcan adapters and CANopen drives: tabbed workspace, SDO client, EDS browser, CiA 402 drive control, plotting, one-file Windows app (fork of CANviz) | Python · TypeScript · CANopen · slcan |
| 🦾 [**FourBar-RealTimeControl-ModelBasedDesign**](https://github.com/MCanKandamar/FourBar-RealTimeControl-ModelBasedDesign) | Real-time PID position and velocity control of a four-bar mechanism, deployed to Arduino and tuned live from a MATLAB app over a binary UART protocol | Simulink · Arduino · MATLAB App Designer |
| 📐 [**imu-tilt-kalman**](https://github.com/MCanKandamar/imu-tilt-kalman) | *(in progress)* Two-state Kalman filter (tilt angle + gyro bias) in portable C++, tested in simulation, on recorded data and live on an STM32 | C++17 · CMake · GoogleTest · CI |
| 🔋 [**Artificial-Neural-Network-Optimization**](https://github.com/MCanKandamar/Artificial-Neural-Network-Optimization) | Li-ion battery SoC estimation with a neural network trained by a custom Levenberg–Marquardt algorithm, plus eight optimization methods written from scratch | MATLAB |
| ✋ [**Hand-Rehabilitation-Robot**](https://github.com/MCanKandamar/Hand-Rehabilitation-Robot-via-Kinematic-Synthesis-Project) | Finger motion tracked from video, then a 1-DOF four-bar mechanism synthesized to reproduce it | MATLAB · Image Processing |

#### 🧰 Tools for AI coding agents

| Project | What it is |
|---|---|
| 🗂️ [**agent-lite**](https://github.com/MCanKandamar/agent-lite) | *Your AI agent forgets. Your repo doesn't.* A small Markdown + git working system that keeps an agent's plan and progress in the repository, so any new session (Claude Code, Codex, …) can continue and recover interrupted work. |
| 🛡️ [**context-guard**](https://github.com/MCanKandamar/context-guard) | A hook for Claude Code and Codex that tells you when a long session should be compacted or restarted, and what to keep. |

---

### 🛠️ Tech stack

**Embedded**<br>
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++20-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![STM32](https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white)
![Arm](https://img.shields.io/badge/Arm%20Cortex--M-0091BD?style=flat-square&logo=arm&logoColor=white)
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-7DB700?style=flat-square)
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
![FOC](https://img.shields.io/badge/FOC%20%C2%B7%20SVPWM%20%C2%B7%20SMO%20%C2%B7%20PID-8A2BE2?style=flat-square)

**Hardware & Tools**<br>
![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white)
![GoogleTest](https://img.shields.io/badge/GoogleTest-4285F4?style=flat-square&logo=google&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Altium](https://img.shields.io/badge/Altium%20Designer-A5915F?style=flat-square&logo=altiumdesigner&logoColor=white)
![KiCad](https://img.shields.io/badge/KiCad-314CB0?style=flat-square&logo=kicad&logoColor=white)
![LabVIEW](https://img.shields.io/badge/LabVIEW-FFDB00?style=flat-square&logoColor=black)
![SolidWorks](https://img.shields.io/badge/SolidWorks-D71920?style=flat-square&logo=dassaultsystemes&logoColor=white)

---

### 📈 Highlights

- 🏁 Reached the motor's maximum **3,560 rpm** in both Hall and sensorless (SMO) modes on a custom STM32G473 FOC drive.
- 🔐 Brought up all three STM32H5 secure boot paths (**STiRoT, OEMiROT, STiRoT + OEMuROT**) with signed, encrypted updates over USB DFU.
- 🏎️ Started a Formula Student team's **first electric vehicle** program and coordinated its HV, LV, battery, embedded and control subteams.
- 📄 Co-author: *Industrial Battery Energy Storage Unit Investigations for Time-Dependent Experimental Characterization*, **IEEE ICECET 2025**, Paris. [DOI: 10.1109/ICECET63943.2025.11472377](https://doi.org/10.1109/ICECET63943.2025.11472377)

---

### 🌍 Languages

🇹🇷 Turkish (native) · 🇬🇧 English (professional) · 🇩🇪 German (elementary)

<p align="center"><i>“From the Simulink model to the 20 kHz interrupt.”</i></p>
