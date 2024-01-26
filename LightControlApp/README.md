# Light_control_app_proyect

Hi there, this project was made to control a room's light and it involves into electronics, you must contain the following hardware components; Arduinouno, ESP32,a relay module. Download ArduinoIDE and Python to support the software that will allow you to implement this project successfully to any room.

## Arduino

### light_control_arduino.ino

The Arduino sketch for controlling the light. Upload this to your Arduino board.

## Python

### `main.py`

The main Python script for the Kivy app. Run this script to control the light.

### `requirements.txt`

List of Python dependencies for the project.

## Virtual Environment

### `venv/`

This directory contains the Python virtual environment for the project. Activate it before running the Python script.

## Getting Started

1. Upload `light_control_arduino.ino` to your Arduino board.
2. Connect ESP32 to the Arduino and upload the ESP32 code.
3. Install Python dependencies by running: `pip install -r python/requirements.txt`.
4. Activate the virtual environment: `source venv/bin/activate` (Linux/Mac) or `venv\Scripts\activate` (Windows).
5. Run the Python script: `python python/main.py`.

## Documentation

For more details, check out the documentation in the project.

## License

This project is licensed under the [MIT License](LICENSE).
