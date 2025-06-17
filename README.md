# Mini--Project
## 💡 Project Overview

Blind and visually impaired individuals face numerous challenges in navigation. This project aims to replace the traditional white cane with a modern, hands-free, electronic assistive device that provides obstacle detection via **sound and vibration feedback**.

## 🎯 Features

- Ultrasonic obstacle detection (up to ~100 cm range)
- Vibration motor and buzzer feedback
- Arduino Nano-based low-cost design
- Wearable and lightweight (e.g., wristband or belt clip)
- Simple and robust circuitry using Zero PCB
- Power-efficient, battery-operated setup

## 🔧 Hardware Used

- Arduino Nano  
- Ultrasonic Sensor (HC-SR04)  
- Piezo Buzzer  
- Vibration Motor  
- Zero PCB  
- 9V Battery with cap  
- Soldering wire & iron  
- Connecting wires, elastic band

## 🛠️ Wiring Overview

| Component         | Arduino Pin |
|------------------|-------------|
| Buzzer (+ve)     | Digital 13  |
| Buzzer (-ve)     | GND         |
| Vibration Motor  | Digital 9   |
| Ultrasonic Trig  | Digital 12  |
| Ultrasonic Echo  | Digital A5  |
| VCC & GND        | VCC, GND    |


🧪 Working
The device sends out ultrasonic pulses and listens for their echo.

If an object is detected within 100 cm, the device triggers vibration and sound alerts.

The alert frequency increases as the object gets closer, helping the user estimate distance intuitively.

✅ Benefits
Cost-effective (under ₹1500)

Hands-free navigation

Can be worn like a band or stitched into clothing

Minimal training required

🚀 Future Scope
Integrate LiDAR for enhanced range and precision

Add Bluetooth or voice alerts for directional guidance

Incorporate rechargeable power banks

Convert into full wearable (e.g., smart jacket or shoe insert)

📄 License
