## Hi, I'm Müslüm Can Kandamar

Mechatronics engineer working on embedded software, motor control and Model-Based Design.

- STM32 firmware in C and C++: FOC motor drives, CANopen (CiA 402), USB, CAN, bootloaders and secure boot
- Control design in MATLAB/Simulink and Simscape, verified in MIL/SIL and deployed with Embedded Coder
- Former electrical department lead of IKC Racing, where I started the team's first electric vehicle program
- B.Sc. in Mechatronics Engineering, İzmir Kâtip Çelebi University

### Featured projects

- **[stm32g4-foc-motor-drive](https://github.com/MCanKandamar/stm32g4-foc-motor-drive)**: BLDC/PMSM drive firmware on STM32G473. 20 kHz FOC with Hall or sensorless sliding-mode observer angle, a CANopen CiA 402 node, fault protection, unit tests and CI. *C++20, FreeRTOS, CANopenNode, GoogleTest*
- **[FOC-ModelBasedDesign-STM32G4](https://github.com/MCanKandamar/FOC-ModelBasedDesign-STM32G4)**: Graduation project. Cascaded FOC of an EV-scale PMSM modeled in Simulink/Simscape, then generated with Embedded Coder for an STM32G474RE bench setup. *MATLAB, Simulink, Simscape, Embedded Coder*
- **[FourBar-RealTimeControl-ModelBasedDesign](https://github.com/MCanKandamar/FourBar-RealTimeControl-ModelBasedDesign)**: Real-time PID position and velocity control of a four-bar mechanism, deployed to Arduino and tuned live from a MATLAB app over UART. *Simulink, Arduino, App Designer*
- **[imu-tilt-kalman](https://github.com/MCanKandamar/imu-tilt-kalman)**: Two-state Kalman filter (tilt angle and gyro bias) in portable C++, tested in simulation, on recorded sensor data and on an STM32. Work in progress. *C++17, CMake, GoogleTest*
- **stm32-slcan** (private repository): USB-to-CAN adapter firmware for STM32F072 with the LAWICEL SLCAN command set over USB CDC, tested with SavvyCAN, python-can and SocketCAN. *C, STM32*

### Skills

**Embedded:** C, C++, STM32, FreeRTOS, ThreadX, CAN/CANopen, USB, UART, SPI, I2C<br>
**Control & MBD:** MATLAB, Simulink, Simscape, Stateflow, Embedded Coder, FOC, PID<br>
**Tools:** CMake, GoogleTest, Git, GitHub Actions, Altium Designer, LabVIEW
