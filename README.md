# Arduino-RFID-LOCK
RFID door lock using Arduino
# RFID Door Lock using Arduino

This project utilizes Arduino to create a simple RFID door lock system. By interfacing an RFID reader with Arduino, users can access a door by swiping RFID tags or cards that are programmed into the system.

## Components Required:
1. Arduino (e.g., Arduino Uno)
2. RFID Reader Module (e.g., MFRC522)
3. Servo Motor
4. RFID Tags or Cards
5. Jumper Wires
6. Breadboard
7. 5V Power Supply (if needed)

## Setup Instructions:
1. **Connect the RFID Reader Module:**
   - Connect the RFID reader module to the Arduino according to the pinout diagram provided by the manufacturer.
   
2. **Connect the Servo Motor:**
   - Connect the servo motor to the Arduino. Typically, the signal pin of the servo motor is connected to a PWM pin on the Arduino, the power pin to 5V, and the ground pin to GND.

3. **Install Libraries:**
   - Install necessary libraries for the RFID reader module. You can download and install them using the Arduino IDE library manager.

4. **Upload the Code:**
   - Upload the Arduino code provided in the project folder to your Arduino board.

5. **Program RFID Tags:**
   - Program the RFID tags or cards that you want to grant access to the door lock system. Each tag will have a unique identifier.

6. **Mount Components:**
   - Mount the RFID reader module and the servo motor onto your door or door frame securely.

7. **Power Up:**
   - Power up the Arduino board using either a USB cable or an external power supply.

8. **Test the System:**
   - Test the system by swiping programmed RFID tags. The servo motor should rotate to unlock the door when a recognized tag is swiped.

## Usage:
1. **Adding New RFID Tags:**
   - To add new RFID tags or cards, modify the Arduino code to include the new tag's unique identifier and upload the code to the Arduino board.

2. **Removing Access:**
   - To remove access for a specific RFID tag, simply remove or comment out the corresponding code line in the Arduino sketch.

3. **Maintenance:**
   - Regularly check the connections and components for any loose connections or damages. Replace any faulty components as needed.

## Note:
- Ensure to keep the Arduino board and components protected from moisture and environmental factors if used outdoors.
- This project provides a basic RFID door lock system and can be further customized or expanded based on specific requirements.

