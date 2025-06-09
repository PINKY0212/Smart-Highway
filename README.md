# Smart Highway System

The **Smart Highway System** is an intelligent transportation solution designed to enhance road safety, reduce fuel consumption, and improve driver comfort. It integrates sensors, Arduino-based hardware, and a custom Android app to automate toll collection, monitor vehicle speed, and control streetlights dynamically. The Smart Highway System demonstrates how IoT and automation can revolutionize road infrastructure by improving safety, reducing energy waste, and streamlining toll collection.  

## Key Features
1. **Automated Toll Collection (ACTS)**  
   - Uses **RFID sensors** and **GSM technology** for cashless toll deduction.  
   - Sends SMS notifications to registered users.  

2. **Speed Detection**  
   - **IR sensors** detect vehicles exceeding speed limits to prevent accidents.  

3. **Smart Streetlights**  
   - **LDR and IR sensors** activate lights only when vehicles pass, saving energy.  

4. **Android App Control**  
   - Manual control of streetlights and toll barriers via a **WiFi-connected app** built on Android Studio.  

## Hardware Components
- **Arduino Mega**: Central microcontroller for sensor integration.  
- **Sensors**:  
  - RFID (for toll collection)  
  - IR (speed detection and streetlight control)  
  - LDR (ambient light sensing)  
- **WiFi Module**: Connects hardware to the Android app.  

## Software Tools
- **EasyEDA**: Circuit design and PCB schematics.  
- **Android Studio**: App development for remote control.  
- **Arduino IDE**: Programming sensor logic and WiFi communication.  

## Methodology
1. **Modular Coding**: Individual C programs for each sensor, combined into a unified system.  
2. **"V" Diagram Approach**: Ensures systematic integration of hardware and software.  
3. **Simulations**: Validated RFID toll deduction, IR speed detection, and streetlight automation.  

## Results
- **App Interface**: Successfully controlled streetlights and toll barriers.  
- **RFID Simulation**: Automated toll deduction with SMS confirmation.  
- **IR Simulation**: Detected speeding vehicles in test scenarios.

## Future Scope
- Expand to multi-lane highways.  
- Integrate solar panels for sustainable energy.  
- Add AI for predictive traffic management.
