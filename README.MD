\# ESP32 LM5069 Control Board for ST3215 Servo Motors



An open-source hardware control board designed around the \*\*ESP32\*\* microcontroller and the \*\*TI LM5069\*\* High-Voltage Positive Hot Swap Controller, specifically built to drive and manage power for \*\*ST3215 servo motors\*\*.



\---



\## Features



\- \*\*Microcontroller:\*\* ESP32 module providing onboard Wi-Fi, Bluetooth, and extensive GPIO/PWM capabilities for wireless telemetry and control.

\- \*\*Power Management:\*\* Texas Instruments LM5069 Hot Swap Controller for robust overcurrent protection, soft-start power-up, and voltage fault handling.

\- \*\*Actuator Support:\*\* Dedicated interfaces and power routing optimized for ST3215 serial bus servo motors.

\- \*\*Custom Design:\*\* Built with Altium Designer, featuring organized schematic sheets, custom footprints, and manufacturing outputs.



\---



\## Repository Structure



```text

├── Gerbers\_and\_drill/      # Fabrication files (Gerber \& NC Drill outputs)

├── Job1.OutJob             # Altium Output Job configuration file

├── PCB1.PcbDoc             # Main PCB layout document

├── Schm.SchDoc             # Schematic design document

├── control\_board\_v2.PrjPcb # Altium project file

├── control\_board\_v2.IntLib # Integrated libraries used in the design

├── v2lib.PcbLib            # Custom PCB component library

└── v2lib.SchLib            # Custom schematic symbol library

