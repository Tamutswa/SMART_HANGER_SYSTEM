# 👕 SMART HANGER SYSTEM

A Smart Hanger System that automatically monitors and adjusts conditions to maintain optimal storage and drying of clothes. This project integrates hardware components with a web-based interface to track environmental factors such as humidity, temperature, and light intensity, and performs intelligent actions accordingly.

## 🚀 Project Overview

The Smart Hanger System is designed to:
- Detect environmental conditions using sensors.
- Automatically retract or expose hangers based on weather data.
- Notify users via an interactive web interface.
- Provide real-time monitoring using IoT integration.

## 🛠️ Features

- 🌡️ Temperature and Humidity Sensing (DHT11)
- ☀️ Light Intensity Monitoring (LDR Sensor)
- 🎛️ Servo Motor Control for Automated Hanger Movement
- 🔌 ESP32-based microcontroller integration
- 🌐 Web interface for real-time monitoring and notifications
- 📶 Wi-Fi connectivity for remote access

## 🧰 Tech Stack

### Hardware
- ESP32 Development Board
- DHT11 Temperature and Humidity Sensor
- LDR Sensor
- Servo Motor
- Jumper Wires, Breadboard, and Power Source

### Software
- Arduino IDE (Embedded Programming)
- HTML/CSS/JavaScript (Frontend Interface)
- Firebase / MQTT (Optional for data communication)
- NodeMCU / MicroPython (optional alternative for control logic)

## 📁 Project Structure
``` SMART_HANGER_SYSTEM/ ├── hardware/ │ └── circuit_diagram.fzz # Fritzing diagrams and schematics ├── firmware/ │ └── smart_hanger.ino # Arduino sketch for ESP32 ├── web/ │ ├── index.html # Main dashboard interface │ ├── style.css # Styling for UI │ └── script.js # JavaScript to handle logic ├── images/ │ └── system_demo.jpg # Demo image of system ├── README.md └── LICENSE ``` 


---

## 🧪 How It Works

1. Sensors read the environment data.
2. Based on set thresholds (e.g., rain or darkness), the hanger system moves clothes to safety.
3. Data is pushed to the web interface using Wi-Fi.
4. Users receive alerts or updates through the dashboard.

---

## 🖼️ System Demo

![System Demo](images/system_demo.jpg)

---

## ⚙️ Installation & Setup

1. Clone this repository:
   ```bash
   git clone https://github.com/Tamutswa/SMART_HANGER_SYSTEM.git
   cd SMART_HANGER_SYSTEM

2.  Upload the firmware to your ESP32 using the Arduino IDE.

3. Serve the web/ folder using any local server (e.g., Live Server, XAMPP, etc.)

4. Connect all hardware components as per the schematic in hardware/circuit_diagram.fzz.

5. Ensure Wi-Fi credentials are set correctly in firmware/smart_hanger.ino.

Let me know if you'd also like to add troubleshooting tips or FAQs in a separate section!

## 📌 To Do

- [ ] Add Firebase/MQTT integration
- [ ] Improve UI/UX on dashboard
- [ ] Add mobile app or voice assistant control
- [ ] Design and print a 3D case for electronics

 ## 🧑‍💻 Author

**Tamutswa Matondo**  
Frontend Developer | Embedded Systems Enthusiast  
📧 [tamutswamatondo04@gmail.com](mailto:tamutswamatondo04@gmail.com)  
📞 +263 783 597 194 | +263 717 029 585  
🔗 [GitHub Profile](https://github.com/Tamutswa)

## 📄 License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgements

- Special thanks to NUST for supporting student innovation.
- Inspired by smart home automation trends in IoT.











