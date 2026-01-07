# Sensors and Data Acquisition

## Sensor Overview
The robot uses multiple sensors to achieve reliable obstacle detection and orientation tracking.

---

## Distance Sensors
### Sharp GP2Y0A21YK0F
- Analog output
- Fast response
- Used for side and frontal obstacle detection

### VL53L0X Time-of-Flight
- Digital I2C interface
- High precision
- Used for accurate frontal distance measurement

---

## Orientation Sensor
### MPU6050 IMU
- Gyroscope and accelerometer
- Used primarily for yaw estimation and stability

---

## Data Handling
Sensor data is sampled periodically, filtered, and passed to the control logic without blocking delays.
