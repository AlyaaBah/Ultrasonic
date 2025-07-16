# Ultrasonic
ultrasonic sensor to detect the proximity of objects.

---

##  Components Used

- Arduino Uno  
- HC-SR04 Ultrasonic Sensor  
- Breadboard  
- Green LED  
- Yellow LED  
- Red LED  
- Buzzer  
- 3 × 220Ω resistors (for LEDs)  
- Jumper wires

---

##  System Description

The ultrasonic sensor continuously measures the distance to the nearest object. Depending on the proximity, the system activates one of three LEDs:
- **Green LED**: Object is within 30 cm  
- **Yellow LED**: Object is within 20 cm  
- **Red LED + Buzzer**: Object is within 10 cm or less

This setup provides a clear and intuitive alert system for distance-based detection, suitable for applications like parking sensors or obstacle detection.

---

##  Wiring Instructions

### Ultrasonic Sensor (HC-SR04):
- **VCC** → 5V  
- **GND** → GND  
- **TRIG** → Digital Pin 7  
- **ECHO** → Digital Pin 6

### LEDs:
- **Green LED Anode** → Digital Pin 8  
- **Yellow LED Anode** → Digital Pin 9  
- **Red LED Anode** → Digital Pin 10  
- **All Cathodes** → GND via 220Ω resistors

### Buzzer:
- **Positive Lead** → Digital Pin 11  
- **Negative Lead** → GND

---

##  Notes

- The system uses the `NewPing` library for accurate distance measurement.
- The buzzer activates only when the object is extremely close (≤10 cm).
- All components are simulated and verified using TinkerCAD Circuits.

---

##  Applications

This project can be adapted for:
- Parking assistance systems  
- Obstacle detection in robotics  
- Proximity-based alerts in automation

⭐ Created by Alyaa

