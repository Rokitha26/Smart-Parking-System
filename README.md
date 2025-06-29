# Smart-Parking-System
🚗 Smart Parking System with Raspberry Pi Pico

A compact and affordable Smart Parking System using Raspberry Pi Pico, IR sensors, servo motor, RGB LED, and buzzer. This project detects car entry and exit, manages parking slots in real time, and provides visual and audible feedback.


---

📌 Features

🔍 IR sensor-based car detection (entry & exit)

🎮 Servo-controlled gate automation

🎨 RGB LED indicators for system status

🔔 Buzzer alerts (short, long, double)

🧠 Slot counter logic with total slot management

🖨 Real-time status display via serial console



---

📁 Components Used

Component Quantity

Raspberry Pi Pico 1
IR Sensors 2
Servo Motor 1
RGB LED (Common Cathode) 1
Buzzer 1
Resistors (as needed) -
Jumper Wires -
Breadboard 1



---

🛠 How It Works

Entry: When a car is detected by the entry IR sensor and slots are available, the gate opens, the car enters, slots decrease by 1.

Full: If no slots are left, the system alerts with red LED and double buzz.

Exit: When a car is detected at the exit, the gate opens, and the slot count is incremented.

Indicators:

Green LED → Car allowed to enter

Red LED → Parking Full

Blue LED → Car exiting

No light → Idle state
