# Three-Para-Patient-Monitoring-System

A low-cost biomedical monitoring system designed to measure **SpO₂ (Blood Oxygen Saturation)** and **Heart Rate** using optical sensing techniques, signal conditioning, embedded systems, and real-time visualization. Developed as a Project Based Learning (PBL) project for Electronics & Telecommunication Engineering. 

📌 Project Overview

This project focuses on developing an affordable and compact patient monitoring solution using:

- Sunrom SpO₂ Sensor Probe
- Arduino UNO
- ADS1115 16-bit ADC
- Python-based GUI
- 7-inch LCD Display
- Custom PCB designed in KiCad

The system captures raw photodiode signals from a medical-grade SpO₂ probe, processes the signals, and displays real-time physiological parameters and waveforms.

---

🚀 Features

- 📈 Real-time SpO₂ monitoring
- ❤️ Heart Rate detection
- 📊 Live waveform visualization
- 🔬 High-resolution signal acquisition using ADS1115
- 🖥️ Python GUI for monitoring dashboard
- 🔌 UART serial communication
- 🧠 Signal processing using NumPy
- 🛠️ Custom PCB implementation using KiCad

---

🧠 Working Principle

The system uses Photoplethysmography (PPG):

1. Red and Infrared LEDs pass light through the fingertip.
2. A photodiode detects the transmitted light intensity.
3. Blood oxygen levels affect Red and IR absorption differently.
4. The analog signal is converted into voltage using a resistor-based I-V converter.
5. ADS1115 converts the signal into high-resolution digital data.
6. Arduino transmits the data to a thin-client system.
7. Python software processes and visualizes the signals.

---

🏗️ Hardware Used

| Component          | Description                       |
| ------------------ | --------------------------------- |
| Arduino UNO R3     | Main microcontroller              |
| Sunrom SpO₂ Probe  | Optical sensing                   |
| ADS1115            | 16-bit ADC                        |
| BC547 Transistors  | LED Driver Circuit                |
| 7-inch LCD         | Display Interface                 |
| Thin Client System | Data processing and GUI           |
| Custom PCB         | Signal conditioning & interfacing |

---

💻 Software Stack

- Python
- NumPy
- PySerial
- Kivy GUI Framework
- VS Code
- KiCad
- Git & GitHub

---

📊 Results

| Parameter        | Expected Range | Obtained Result             |
| ---------------- | -------------- | --------------------------- |
| SpO₂             | 95–100%        | 95–100%                     |
| Heart Rate       | 72–90 BPM      | Approximate values obtained |
| Waveform Display | Real-time      | Successfully implemented    |

The project successfully demonstrated real-time signal acquisition and visualization with acceptable SpO₂ accuracy. 

---

⚡ Challenges Faced

- AC noise interference
- Signal spikes
- Motion-based variations
- Lack of oscilloscope for FFT analysis
- Difficulty in designing filters
- Respiratory rate implementation challenges

Software averaging and hardware filtering techniques were implemented to improve signal quality.

---

🔮 Future Scope

- Advanced noise filtering
- Op-Amp based Transimpedance Amplifier
- Respiratory Rate implementation
- ECG integration
- Remote patient monitoring
- IoT connectivity
- Mobile app support
- Clinical-grade calibration

---

📷 Project Highlights

- Custom-designed PCB
- Real-time monitoring dashboard
- Medical sensor interfacing
- Biomedical signal processing
- Embedded + Software integration

---

👨‍💻 Team Members

- Mayank Thakkar
- Sneha Jadhav
- Anjali Sawant
- Aryan Aich

Guide: Dr. S. D. Shingade

Department of Electronics & Telecommunication Engineering
Pune Institute of Computer Technology

---

🙏 Acknowledgement

Special thanks to:

- Dr. S. D. Shingade
- Yashka Infotronics Pvt. Ltd.
- CAD Team & Mentors for guidance and support throughout the project development. 

---

📚 References

- Medical Instrumentation – John G. Webster
- Programming Arduino – Simon Monk
- ADS1115 Datasheet
- Sunrom SpO₂ Sensor Documentation

---

📜 License

This project is developed for academic and educational purposes.
