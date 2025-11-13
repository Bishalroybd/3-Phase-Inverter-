Arduino 3-Phase Inverter
A compact three-phase inverter using Arduino Uno and power MOSFETs to convert 12V DC to three-phase AC power with 120° phase displacement.

🚀 Quick Overview
Input: 12V DC

Output: 223V AC per phase (386V line-to-line)

Power: 60W per phase (180W total)

Controller: Arduino Uno R3

Switching: 18 × IRFZ44N MOSFETs

Waveform: Square wave (sine wave improvement in progress)

🔧 Key Features
Three-phase output with 120° phase displacement

PWM-controlled MOSFET switching

Step-up transformers for voltage amplification

Suitable for microgrid and renewable energy applications

📁 Project Structure
text
3-phase-inverter/
├── Hardware/          # Circuit schematics & PCB
├── Software/          # Arduino code
├── Documentation/     # Datasheets & calculations
└── Simulation/        # Proteus files
⚡ Current Improvement
Converting square wave to pure sine wave output for better efficiency and reduced harmonics.

🛠️ Components
Arduino Uno R3

IRFZ44N MOSFETs (18x)

Center-tapped transformers (3x)

12V Battery

60W bulbs (3x for load testing)
