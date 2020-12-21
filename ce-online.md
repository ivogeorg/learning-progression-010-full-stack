
# Lesson & assignments after 008

## Hardware branch
1. Need better serial support, in particular I2C. This will lead to micro:bit peripherals.
   1. Sensors & actuators.
   2. External memory.
   3. WiFi.
2. Lookup tables after multiplexors. This leads to FPGAs.
3. As a continuation of logic gates and computational components, FPGA (say, [TinyFPGA](https://tinyfpga.com/)) programming after 008 (logic gates) and 009 (computation).
4. FPGAs lead to designing computers (probably just 8-bit ones with TinyFPGA).
5. This may lead to Verilog-programmable FPGA (probably higher-end), then transition to denser fabric designs for VLSI, and further into ASIC and SOC design.
   - Google TPU
6. RISC-V.
7. Novel processor design (ML, AI, etc).
   1. Architectures at [ScaledML 2020](http://scaledml.org/2020/)
   
### Devices
1. micro:bit
2. Arduino
3. Raspberry Pi
4. SparkFun Artemis.

### Measurement
1. [Multimeters](https://healthyhandyman.com/best-budget-multimeters-guide/)
2. [Digilent Analog Discovery 2](https://store.digilentinc.com/analog-discovery-2-100msps-usb-oscilloscope-logic-analyzer-and-variable-power-supply/)

## Software branch
1. [micro:bit software stack](https://mattwarren.org/2017/11/28/Exploring-the-BBC-microbit-Software-Stack/).
2. [mbed programming in C/C++](https://www.iot-programmer.com/index.php/books/27-micro-bit-iot-in-c/chapters-micro-bit-iot-in-c/1-getting-started-with-c-c-on-the-micro-bit?showall=1) (bypassing the micro:bit DAL/runtime)
   - Better I2C support.
3. RTOS (mbed 5)
4. (?) Encoding & decoding (vast topic with wide implications, almost a branch of its own and/or graduate level work)

## Full-stack computer integration
1. Embedded systems.
2. IoT.
3. micro:bit extension packages.
4. Domain-specific hardware and software stacks.
   1. Hennessy & Patterson [Turing](https://www.acm.org/hennessy-patterson-turing-lecture) [Lecture](https://iscaconf.org/isca2018/turing_lecture.html) topics. ([Slides](https://iscaconf.org/isca2018/docs/HennessyPattersonTuringLectureISCA4June2018.pdf))
      1. Domain-Specific Hardware/Software Co-Design
      2. Enhanced Security
      3. Open Instruction Sets
      4. Agile Chip Development
   2. Robotics.
   3. Autonomous vehicles.
   4. SDR.
   
## Comms, networking, and security
1. micro:bit
   1. Radio
   2. BLE stack & profile


# MSU Denver CPE

- [Curriculum](https://www.msudenver.edu/cpe/curriculum/)
- [Program](https://www.msudenver.edu/cpe/program/)
- [Catalog entry](https://catalog.msudenver.edu/preview_program.php?catoid=26&poid=6946#)

1. Problematic CE topics:
   - comms (a & d comms, advanced comms): _requires potentially expensive equipment_
   - power: _safety considerations_
     - actually missing from CPE
     - some in [EET](https://www.msudenver.edu/eet/)
   - VLSI: _requires expensive equipment_
   - AC circuits: _requires oscilloscope_
2. CE topics with no labs:
   - signals & systems
   - solid state device fundamentals (solid state electronics uses discrete elements and the lab is on uses)
   - a & d comms
   - control systems
   - computer networks
   - system reliability
   - security
   - multimedia
3. Missing from curriculum:
   - OS
   
# ACM CE 2016

- [ACM Curricula](https://www.acm.org/education/curricula-recommendations)
- [CE 2016](https://www.acm.org/binaries/content/assets/education/ce2016-final-report.pdf)

1. ACM Curricula:
   1. Computer Engineering
   2. Computer Science
   3. Information Systems
   4. Information Technology
   5. Software Engineering

