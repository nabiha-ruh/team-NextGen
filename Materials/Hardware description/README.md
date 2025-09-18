## Equipment Description  

### 1. Ultrasonic Sensor
- **Purpose:** Used to detect obstacles such as walls or nearby objects.  
- **Reason for Use:** Provides accurate distance measurement using sound waves. It helps the vehicle avoid collisions and navigate safely in indoor/outdoor environments.  

### 2. ESP32 Microcontroller
- **Purpose:** Acts as the main controller of the system.  
- **Reason for Use:** Chosen for its built-in WiFi, Bluetooth, fast processing speed, and sufficient GPIO pins to connect multiple sensors and actuators.  

### 3. Servo Motor (Steering Control)
- **Purpose:** Controls the steering angle of the vehicle.  
- **Reason for Use:** Provides precise angular motion, making it suitable for left/right steering.  

### 4. Gyroscope (Turn Counting & Orientation)
- **Purpose:** Tracks the number of turns and monitors the orientation of the vehicle.  
- **Reason for Use:** Ensures accurate path tracking and helps in navigation when GPS is not available.  

### 5. DC Motor + TB6612FNG Motor Driver
- **Purpose:** DC motor provides the forward and backward movement of the vehicle. The TB6612FNG driver regulates motor speed and direction.  
- **Reason for Use:** Reliable, efficient motor control with PWM support for speed variation.  

### 6. HuskyLens AI Camera
- **Purpose:** Performs object detection and recognizes traffic signals based on color detection.  
- **Reason for Use:** Simplifies AI tasks with built-in vision algorithms, reducing the need for heavy image processing on the ESP32.

### 7. Voltmeter
- **Purpose:** Monitors the battery voltage in real time.  
- **Reason for Use:** Prevents deep discharge, helps track power usage, and ensures stable power supply for all components.
-  
### 8. Power Kill Switch
- **Purpose:** Acts as a safety switch to instantly cut off power to the system.  
- **Reason for Use:** Ensures safe operation and allows immediate shutdown during emergencies or troubleshooting.  

### 9. Push Button
- **Purpose:** Provides manual input to start, stop, or trigger specific functions.  
- **Reason for Use:** Simple and reliable method for user interaction and system control.  

