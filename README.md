# E-bike Smart Motor Controller (Regen + Cruise)

### 📌 Overview
Prototype e-bike motor controller implementing throttle-based PWM control, cruise-assist, and regenerative braking measurement. Displays speed and recovered energy on LCD; measures current via ACS712 to estimate energy returned to the battery.

### ⚡ Features
- Throttle to PWM motor control
- Cruise assist with setpoint toggle
- Brake-triggered regenerative mode with energy accumulation (Wh)
- Speed from wheel Hall sensor and LCD display

### 🛠️ Components Required
- Arduino UNO
- Hall speed sensor (or reed/hall)
- Throttle potentiometer (or throttle input)
- Brake switch
- ACS712 current sensor (or equivalent)
- MOSFET motor driver / ESC (PWM input)
- 16x2 LCD
- Wiring, power supply, and safety circuits

### ⚠️ Notes
- Regen mode here is a prototype: real regenerative braking requires proper power electronics and safe charge path to battery.
- Calibrate ACS712 zero and sensitivity for accurate current measurements.
- Ensure motor driver and battery are rated for your e-bike voltages and currents.

---

👨‍💻 **Author:** K. Viswanadh
