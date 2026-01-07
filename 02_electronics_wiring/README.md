# Electronics and Wiring

## Architecture
The electronic system follows a centralized control model where a single microcontroller manages all sensors and actuators.

---

## Controller
- Arduino Nano
- Responsible for motor control, sensor data acquisition, and decision logic

---

## Motor Drivers
- Two TB6612FNG dual H-bridge motor drivers
- Each driver controls two motors
- PWM-based speed control with direction pins

---

## Wiring Strategy
- Dedicated PWM pins for each motor
- Common ground across all subsystems
- Separation of power and signal lines
- Noise reduction through short wiring paths
