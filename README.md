# electrical-task-3-1

**Project: Proximity-Activated LED with Manual Override**  

This circuit creates an interactive lighting system that responds to its environment in two ways:  

1. **Automatic Proximity Detection**  
The LED activates automatically when objects come within close range, using distance-sensing technology to trigger illumination precisely when needed.  

2. **Instant Manual Control**  
A physical override switch provides direct human control, allowing immediate LED activation regardless of environmental conditions - perfect for testing or priority situations.  

Built with reliability in mind, the system includes intelligent diagnostics that verify all connections during startup. This ensures stable operation and helps identify any setup issues immediately.  

The design demonstrates core principles of interactive electronics by blending:  
- Environmental sensing (automatic response)  
- Physical interfaces (manual control)  
- System self-checks (error prevention)  

Ideal for learning applications, prototyping, or as a foundation for more complex automated lighting systems. The straightforward approach makes it easy to understand while offering practical functionality.  

# electrical-task-3-2

**Arduino Temperature & Distance Sensor Setup**  

This project uses an Arduino to measure **temperature** (LM35 sensor) and **distance** (HC-SR04 ultrasonic sensor).  

### **How It Works**  
1. **Temperature Sensor (LM35)**  
   - Sticks out a voltage that changes with temperature.  
   - Arduino reads it and converts it to Celsius.  

2. **Ultrasonic Sensor (HC-SR04)**  
   - Sends a sound pulse and listens for the echo.  
   - Arduino calculates distance based on how long the echo takes.  

### **What You Get**  
- **Real-time readings** in the Serial Monitor:  
  - Temperature in °C.  
  - Distance in cm.  

![image]
