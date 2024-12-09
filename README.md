# 🧪Automated_Acid_Diluting_System

The Automated Acid Diluting System is an advanced microcontroller-based solution designed to revolutionize acid dilution processes in laboratory environments. By addressing critical safety challenges and introducing precise automation, this system represents a significant leap forward in chemical handling technology.

![alt text](https://github.com/darkgrecher/Automated_Acid_Diluting_System/blob/2a23423491a09dfd956d9208ffddfa4a98f85b98/Demo/demo01.jpg)



https://github.com/user-attachments/assets/80895124-37fe-46e5-9f64-0053e5f4dadd








## 📋 Table of Contents

- [The Problem]()
- [Key Features]()
- [System Components]()
- [Quick Start]()
    - [Prerequisites]()
    - [Installation]()
    - [Usage]()
- [Project Structure]()
- [Contributors]()
- [Contributing]()
- [Acknowledgments]()
- [License]()

## 🚨 The Problem

Manual acid dilution is fraught with risks:

- 🔬 Incorrect acid concentrations
- 💧 Accidental spills
- ☢️ Harmful chemical exposure
- 📚 Lack of expertise in educational settings

## 🌟 Key Features

- **🤖 Automated Acid Dilution**: Minimizes human error and manual handling
- **🛡️ Real-time Safety Checks**: Emergency shutdown and environmental monitoring
- **📏 Precise Measurement**: Time-of-Flight (TOF) sensors for accurate water dilution
- **🔍 Multi-sensor Integration**: Gyroscope, ultrasonic, and temperature sensors
- **👥 User-Friendly Interface**: Simple keypad and LCD display
- **💰 Cost-Effective**: Built with affordable, accessible components

## 🛠 System Components

| Component | Purpose |
| --- | --- |
| ESP32 Microcontroller (2x) | Communication and control |
| VL53L0X Time-of-Flight Sensor | Precise water level measurement |
| Ultrasonic Sensors (2x) | Beaker and liquid detection |
| DS18B20 Temperature Sensor | Liquid temperature monitoring |
| GY-521 MPU-6050 Gyroscope | System leveling |
| Water Pump & Solenoid Valve | Water flow management |
| DC Motors & L298N Driver | Mechanical component operation |

## 🚀 Quick Start

### Prerequisites

- Arduino IDE
- ESP32 Boards
- Hardware components

### Installation

1. Clone the repository
    
    ```bash
    git clone <https://github.com/darkgrecher/automated-acid-dilution.git>
    cd automated-acid-dilution
    
    ```
    
2. Install Dependencies
    - ESP32 libraries
    - Sensor-specific libraries (listed in documentation)
3. Upload Code
    - Connect ESP32 boards
    - Upload respective code via Arduino IDE

### Usage

1. Power on the system
2. Input parameters via keypad
3. Watch automated acid dilution with real-time LCD feedback
4. Rely on built-in safety mechanisms

## 📂 Project Structure

```
automated-acid-dilution/
│
├── code/
│   ├── esp_board_a/
│   └── esp_board_b/
│
├── documentation/
│   ├── project_report.pdf
│   └── code_review.pdf
│
├── hardware/
│   ├── schematic.jpg
│   ├── block_diagram.png
│   └── flow_chart.jpg
│   
├── code/
│   ├── demo01.mp4/
│   └── demo02.mp4/
│   
└── README.md

```

## 👥 Contributors

- **Hashan Rajakaruna(Team Leader)**: ToF Sensor Integration, Mechanical Design, Integration of all components
- **G.D. Punchihewa**: ESP32 Communication, Water Pump Control
- **H.M.M.D. Herath**: Gyroscope, PCB Design
- **S.J. Mayadunna**: Ultrasonic Sensors, LCD Display, Keypad
- **C.B.R.N.D. Bandara**: Temperature Sensor, Buzzer, Finishing

## 🤝 Contributing

Contributions are welcome! Please:

- Submit pull requests
- Report issues
- Suggest improvements

## 🙏 Acknowledgments

Special thanks to the University of Moratuwa Faculty of Information Technology for their support.

## 📄 License

```
MIT License

Copyright (c) 2024 Hashan Rajakaruna

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

*Innovating laboratory safety, one drop at a time* 💧🔬
