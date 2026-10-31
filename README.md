# Water Quality Monitor (ESP32)

An IoT water quality monitor that measures pH, turbidity and temperature in real time.

![Water quality testing device](images/water-quality-testing.jpg)

> Add a short demo video or a screenshot of your readings here if you have one.

## Features

- Measures pH, turbidity and temperature
- Real-time readings from dedicated sensors
- IoT-enabled: readings can be viewed remotely (describe how: serial monitor, web page, dashboard, etc.)
- Written in embedded C++ for the ESP32

## Parts list

| Part | Quantity | Notes |
| --- | --- | --- |
| ESP32 development board | 1 | |
| pH sensor (with signal board) | 1 | Fill in the model |
| Turbidity sensor | 1 | Fill in the model |
| Temperature sensor | 1 | Fill in the model (e.g. DS18B20) |
| Fourth sensor, if any | | Remove this row if not used |
| Resistors, jumper wires, breadboard | | |
| Power supply | 1 | |

## Wiring

| Sensor | ESP32 pin |
| --- | --- |
| pH sensor | GPIO __ |
| Turbidity sensor | GPIO __ |
| Temperature sensor | GPIO __ |

Add a wiring diagram or a photo of the circuit in the `images/` folder and link it here.

## Getting started

1. Install the [Arduino IDE](https://www.arduino.cc/en/software) and add ESP32 board support through the Boards Manager.
2. Install any libraries the sketch needs (for example, for your temperature sensor). List them here.
3. Clone this repository:
   ```bash
   git clone https://github.com/Ehiejakhian/Water-Quality-Monitor-ESP32.git
   ```
4. If the device connects to Wi-Fi, set your network details in the config section of the sketch. Never commit real passwords to a public repo.
5. Open the sketch in the Arduino IDE, select your ESP32 board and port, and upload.

## Calibration

pH and turbidity sensors need calibrating to give accurate readings. Describe how you calibrated yours (for example, using pH 4 and pH 7 buffer solutions) and any known limits of the readings.

## How it works

1. The ESP32 reads each sensor at a set interval.
2. It converts the raw values into pH, turbidity and temperature.
3. It reports the results (serial monitor, web page or dashboard).

Update these steps to match what your code does.

## What I learned / next steps

- What worked well:
- What I'd improve (for example, data logging, alerts when readings go out of range, or a waterproof enclosure):

## Author

Built by [Ehi Ejakhian](https://ehiejakhian.github.io). See more of my projects on my [portfolio](https://ehiejakhian.github.io/embedded-sys/).
