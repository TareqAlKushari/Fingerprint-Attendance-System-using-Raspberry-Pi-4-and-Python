# Fingerprint Attendance System using Raspberry Pi 4 and Python

This repository contains the source code and resources for a **Fingerprint Attendance System** designed to provide a reliable and efficient way of recording and managing the attendance of students or employees using fingerprint sensors and a Raspberry Pi 4.

## Overview

The project leverages the power of biometric authentication to automate the attendance process. By integrating a fingerprint sensor with a Raspberry Pi 4 and Python, this system ensures secure, fast, and accurate attendance logging, eliminating the possibility of proxy attendance or manual errors.

## Features

- **Biometric Authentication:** Uses fingerprint recognition for secure identification.
- **Automated Attendance Logging:** Instantly records attendance upon successful fingerprint match.
- **User Management:** Add, remove, or update registered users.
- **Raspberry Pi Integration:** Low-cost, portable, and energy-efficient hardware.
- **Extensible & Customizable:** Built with Python for easy modification and feature extension.

## Hardware Requirements

- Raspberry Pi 4 (any model with USB or GPIO support)
- Fingerprint sensor module (e.g., R305, GT-521F52, or similar)
- MicroSD card with Raspberry Pi OS installed
- Power supply for Raspberry Pi 4
- (Optional) LCD display, buzzer, or LEDs for notifications

## Software Requirements

- Python 3.x
- Required Python libraries (see `requirements.txt`, if available)
- Fingerprint sensor library (compatible with your sensor model)
- (Optional) SQLite or other database for attendance records

## Getting Started

1. **Clone this repository:**
   ```bash
   git clone https://github.com/TareqAlKushari/Fingerprint-Attendance-System-using-Raspberry-Pi-4-and-Python.git
   cd Fingerprint-Attendance-System-using-Raspberry-Pi-4-and-Python
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
   *(Or install required libraries as listed in the documentation/code.)*

3. **Connect the fingerprint sensor** to the Raspberry Pi according to the sensor's datasheet.

4. **Configure the system** by editing the configuration files if necessary.

5. **Run the attendance system:**
   ```bash
   python main.py
   ```
   *(Replace `main.py` with the actual entry point if different.)*

## Usage

- Enroll new users with their fingerprints.
- Users scan their fingerprints to mark attendance.
- Attendance data is stored and can be exported or analyzed.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for bug fixes, new features, or documentation improvements.

## License

[No license specified.]

## Contact

For more information and updates, visit the [repository](https://github.com/TareqAlKushari/Fingerprint-Attendance-System-using-Raspberry-Pi-4-and-Python) or contact [@TareqAlKushari](https://github.com/TareqAlKushari).

---
*Making attendance smarter, faster, and more secure with biometrics!*
