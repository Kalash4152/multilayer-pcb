🖥️ My First Multi-Layer IoT PCB

This project is my first 4-layer PCB design, created as a multi-purpose IoT sensing board. The idea was to combine multiple sensing capabilities and essential peripherals into a single compact board that could serve as a foundation for different IoT applications.

🔧 Features

ESP32 as the main controller (WiFi + Bluetooth support)

Integrated sensors:

Temperature sensor

Light sensor

Sound sensor

Onboard peripherals:

USB port for communication and power

SD card slot for storage

Built-in memory card interface for data logging

Multi-purpose design → enables IoT prototyping, monitoring, and data collection in one platform

⚡ PCB Design Process

The board was designed in KiCad, with a focus on building a manufacturable and reliable 4-layer PCB.

Layer Stackup:
I applied the concepts of core and pre-preg to design the stackup properly. This allowed me to dedicate separate planes for power and ground, while keeping signal traces isolated and routed cleanly.

Footprints:
I used SnapEDA extensively for verified footprints of external components. For parts not available, I created custom footprints, ensuring correct pad sizes, clearances, and pin alignments.

Routing & Planes:

Power lines were routed with wider traces for better current handling

Ground lines and planes were carefully managed to reduce noise and ensure a solid reference plane

Signal lines were routed with attention to length, separation, and their role in the circuit (high-speed, analog, digital, etc.)

Zones were filled (power/ground) depending on the layer and requirement to maintain proper distribution and minimize EMI

Verification:

Conducted a full ERC (Electrical Rule Check) to eliminate schematic-level errors

Performed DRC (Design Rule Check) and ensured zero errors

Verified every footprint and component placement for manufacturing accuracy

📐 Learning Outcomes

Practical experience in multi-layer PCB design and the importance of proper stackup planning

Gained knowledge about separating power, ground, and signal routing for noise-free operation

Understood the importance of zone fills and copper planes in stable power delivery

Learned to balance auto-routing and manual routing for cleaner signal paths

Developed confidence in using KiCad + SnapEDA workflow for professional PCB design

🚀 Conclusion

This board was my first step into multi-layer IoT hardware design, combining sensors, storage, and communication in one platform. The process gave me valuable insight into PCB stackups, routing strategies, and verification techniques, which will help me in designing more complex boards in the future
