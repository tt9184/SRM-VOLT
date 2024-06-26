
# VOLT
 
## Classroom Access and Electricity Management System

This project is designed to manage classroom access and electricity usage efficiently. It consists of an RFID reader, a keypad for master access, an LCD display, a microcontroller (ATmega328P), relays, and buzzers. The system tracks which faculty members are accessing the classroom and controls electricity usage based on classroom occupancy.

## Features

- **RFID Reader**: Detects and authenticates faculty members accessing the classroom.
- **Keypad**: Provides master access for administrators.
- **LCD Display**: Shows the current user accessing the room.
- **Microcontroller (ATmega328P)**: Manages the entire system.
- **Relays**: Controls the power supply to the classroom.
- **Buzzers**: Alerts for unauthorized access or other important notifications.
- **Electricity Management**: Turns off electricity when the classroom is not in use and limits usage during class hours to conserve energy.

## Components

- RFID Reader
- Keypad
- LCD Display
- Microcontroller (ATmega328P)
- Relays
- Buzzers
- Power Supply

## Installation

1. **Clone the Repository**: 
    ```bash
    git clone https://github.com/yourusername/Classroom-Access-Management.git
    ```
2. **Hardware Setup**:
    - Connect the RFID reader to the microcontroller.
    - Connect the keypad to the microcontroller.
    - Connect the LCD display to the microcontroller.
    - Connect the relays to control the power supply.
    - Connect the buzzers for notifications.
    - Ensure the power supply is correctly connected to all components.

3. **Upload Code**:
    - Open the project in Arduino IDE.
    - Select the correct board and port.
    - Upload the code to the ATmega328P microcontroller.

## Usage

1. **Accessing the Classroom**:
    - Swipe the RFID card on the reader.
    - If authenticated, the LCD display will show the name of the faculty member.
    - The relay will switch on the power supply for the classroom.

2. **Master Access**:
    - Enter the master code on the keypad to access administrative functions.

3. **Electricity Management**:
    - The system will automatically turn off electricity when the classroom is not in use.
    - During class hours, electricity usage is limited and monitored.

## Configuration

- **RFID Tags**: Add or remove RFID tags in the code to manage access.
- **Master Code**: Set the master code in the code for administrative access.
- **Electricity Settings**: Configure the power management settings in the code.

## Contributing

Contributions are welcome! Please submit a pull request or open an issue to discuss any changes or improvements.

