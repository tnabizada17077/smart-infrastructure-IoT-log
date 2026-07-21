## 🟢 Course 3: Introduction to the Internet of Things and Embedded Systems (University of California, Irvine)

### Module 1: IoT Definition and Impact
*   **Resource Constraints:** IoT edge nodes operate under tight energy, memory, and latency limits compared to general-purpose computing platforms.
*   **Enabling Technologies:** The expansion of low-cost silicon, reduced power draw, and widespread network connectivity drives pervasive IoT adoption.
*   **Security & Privacy:** Always-on, connected edge sensors expand the network attack surface, introducing user privacy and system security risks.

### Module 2: Embedded Systems
*   **Compute Core Architecture:** Microcontrollers (MCUs) handle low-power, low-latency control tasks, Microprocessors (MPUs) execute full OS workloads, and FPGAs provide programmable hardware logic.
*   **Transducer Subsystems:** Sensors measure physical phenomena and convert them into electrical inputs, while actuators convert electrical outputs into physical mechanical or thermal actions.
*   **Mixed-Signal Conversion:** Analog-to-Digital Converters (ADCs) map continuous real-world signals into discrete binary registers, while DACs synthesize analog signals from digital logic.

### Module 3: Hardware/Software Components
*   **Datasheet Interpretation:** Component selection requires extracting electrical tolerances ($V_{max}, I_{max}$), thermal operating ranges, and pinout configurations directly from IC datasheets.
*   **Firmware Execution Models:** Compiled C/C++ provides minimal memory footprints and direct register access, whereas interpreted Python offers faster prototyping at the cost of higher RAM usage and slower execution.
*   **Embedded OS Architectures:** Bare-metal systems execute single-loop or interrupt-driven firmware, whereas RTOS and Embedded Linux provide multi-tasking, thread scheduling, and concurrency management.

### Module 4: Networking and the Internet
*   **Network Hardware & Topologies:** Routers, switches, and hubs manage data routing and packet switching across LAN and WAN architectures.
*   **Protocol Layering:** OSI and TCP/IP protocol stacks govern data encapsulation, enabling edge device communication across static networks and Mobile Ad-Hoc Networks (MANETs).
*   **Traffic Diagnostics:** Packet analyzers like Wireshark capture and decode live network traffic to verify data payloads, inspect transport headers, and debug connection failures.

---
THE END