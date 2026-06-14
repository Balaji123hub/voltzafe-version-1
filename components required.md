Hardware Components
Controllers
3 × ESP32 Dev Boards
Voltage Monitoring
3 × ZMPT101B AC Voltage Sensors
Protection & Indication
2 × 5V Relay Modules (Node1, Node2)
3 × Red LEDs
3 × Green LEDs
3 × Buzzers
6 × 220Ω Resistors (for LEDs)
Relay Driver Circuit
2 × BC547 Transistors
2 × 1kΩ Resistors (BC547 base resistors)
Reset System
2 × Push Buttons (Node1, Node2)
Communication
ESP-NOW (built into ESP32, no extra hardware)
Power
USB Power Supply / Laptop USB
Breadboards
Jumper Wires
Software
Development
Arduino IDE
Libraries
WiFi.h
esp_now.h
System Architecture
Node1 (Master)
├── ESP32
├── ZMPT101B
├── Relay
├── BC547
├── Red LED
├── Green LED
├── Buzzer
└── Reset Button

Node2 (Protection Node)
├── ESP32
├── ZMPT101B
├── Relay
├── BC547
├── Red LED
├── Green LED
├── Buzzer
└── Reset Button

Node3 (Monitoring Node)
├── ESP32
├── ZMPT101B
├── Red LED
├── Green LED
└── Buzzer
