# Rectenna 
A dual-band rectenna system for harvesting RF energy at 3.5 GHz and 5 GHz frequencies.

# Dualband Rectenna System for RF Energy Harvesting and Wireless Power Transfer

This project presents a **dual-band rectenna system** capable of harvesting ambient electromagnetic energy at **3.5 GHz and 5 GHz**, suitable for powering small electronic gadgets and IoT devices. The system was developed to explore efficient wireless energy harvesting using reconfigurable antennas and optimized rectifying circuits.



##  Need for the Project

With the rapid growth of **IoT and low-power embedded systems**, there is a need for **sustainable, wireless energy solutions**. Conventional batteries are limited by size and lifespan. This project addresses the problem by designing a system that **converts ambient RF signals (Wi-Fi & 5G) into usable DC power**, minimizing the need for physical charging.


##  Features & Workflow

- ✔ Dual-band microstrip patch transmitting antennas (3.5 GHz and 5 GHz)
- ✔ Frequency-reconfigurable receiving antenna using PIN diodes
- ✔ Custom-designed RF-to-DC rectifier with filter
- ✔ Efficiency tested using a Vector Network Analyzer (VNA)
- ✔ Output voltage between **2.5V – 5V** with **80–85% efficiency**

## Workflow:

Research & Problem Identification
           ↓
Transmitting Antenna Design (3.5 & 5 GHz)
           ↓
Reconfigurable Receiver Antenna with PIN Diodes
           ↓
Rectifier Circuit (RF to DC)
           ↓
System Integration & PCB Fabrication
           ↓
Testing using VNA & Multimeter
           ↓
Efficiency Measurement (Output: 2.5–5V, 80–85%)
           ↓
Documentation & Publication

1. Literature Survey & Problem Identification
	•	What: Explored existing energy harvesting methods and limitations in powering low-energy devices wirelessly.
	•	Why: Identified the opportunity to harness ambient RF signals (especially from Wi-Fi and 5G) to generate DC power.
	•	How: Reviewed IEEE papers, journals, and recent advancements in rectenna systems to define objectives.


2. Design of Transmitting Antennas
	•	What: Designed two microstrip patch antennas to transmit RF signals at 3.5 GHz and 5 GHz.
	•	Why: These are common frequency bands with strong signal presence in urban areas (Wi-Fi & 5G).
	•	How: Used CST Microwave Studio to simulate and optimize antenna dimensions, S11 return loss, and radiation patterns.


3. Design of Frequency-Reconfigurable Receiving Antenna
	•	What: Created a V-shaped antenna with PIN diodes that allows switching between 3.5 GHz and 5 GHz.
	•	Why: A single compact antenna that supports multiple bands is more efficient and space-saving.
	•	How: PIN diodes are biased using small DC voltage to reconfigure the antenna’s resonant frequency dynamically.


4. Rectifier Circuit Development
	•	What: Built an RF-to-DC rectifier using Schottky diodes, matching network, and filter circuit.
	•	Why: Converts the captured RF signals into usable DC output for powering small electronics.
	•	How: Designed using KiCad/Eagle and verified for voltage regulation, ripple reduction, and efficiency.


5. System Integration
	•	What: Connected the transmitting antennas, reconfigurable receiving antenna, rectifier, and output measurement tools.
	•	Why: Full rectenna system must function in real-time to validate energy harvesting and power delivery.
	•	How: Assembled on prototype boards, connected via coaxial cables, and housed in a test rig.


6. Simulation and Fabrication
	•	What: Simulated all individual components for performance before building.
	•	Why: Ensures accuracy, efficiency, and saves cost before physical fabrication.
	•	How: Used simulation tools (CST, HFSS), then fabricated antennas and PCBs on Rogers substrate.


7. Testing and Measurement
	•	What: Tested the system using a Vector Network Analyzer (VNA) and digital multimeter.
	•	Why: To measure output voltage, return loss, bandwidth, and overall power conversion efficiency.
	•	How: Connected VNA to transmitting antenna, monitored RF signal, observed DC output from rectifier.


8. Result Evaluation
	•	What: Collected performance data — DC output between 2.5V–5V, efficiency up to 85%.
	•	Why: Validates the system as a practical energy harvesting solution for small gadgets and sensors.
	•	How: Compared simulation data with physical test results, plotted efficiency curves, and documented findings.


9. Documentation & Publication
	•	What: Compiled all findings, results, and methodology into a research paper.
	•	Why: Shared the innovation with the academic and research community.
	•	How: Published in Atlantis Press (Springer Nature) through ICARECS 2025 conference.

## Test Results:

|   Parameter                          |   Measured Value                          |
|--------------------------------------|-------------------------------------------|
| Frequency Bands                      | 3.5 GHz and 5 GHz                         |
| Antenna Reflection Coefficient (S11) | -21.5 dB (3.5 GHz), -35 dB (5 GHz)        |
| Output DC Voltage                    | 2.5V to 5V                                |
| Power Conversion Efficiency          | 80% to 85%                                |
| Output Stability                     | Stable under continuous RF exposure       |
| Tools Used                           | Vector Network Analyzer, Multimeter       |
| Application Target                   | IoT nodes, sensors, embedded systems      |

## Testing photos:
![rectenna test result 1](https://github.com/user-attachments/assets/af3e4905-ef9e-43fb-9b43-e4606ac2219e)

![rectenna test result 2](https://github.com/user-attachments/assets/880c6c98-382e-46f5-a711-7785c75859e5)

## Tech Stack & Tools

   HFSS (Ansys) –  EM simulation
   Hardware – Vector Network Analyzer, Multimeter, PIN Diodes, Rogers Substrate,Soldering Tools, Biasing kits, Coaxial connectors


## Published Paper

This project is based on the published research paper:

“Dualband Rectenna Systems for RF Energy Harvesting and Wireless Power Transfer in Small Electronic Gadgets”
Published in: Proceedings of ICARECS 2025
Publisher: Atlantis Highlights in Engineering, Springer Nature
🔗 View Paper on Atlantis Press:- https://doi.org/10.2991/978-94-6463-754-0_10

