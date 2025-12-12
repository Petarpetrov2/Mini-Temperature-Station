# Mini Temperature Station
A simple and affordable temperature‑monitoring system designed for small greenhouses or indoor environments.
The project measures ambient temperature using a sensor and provides a visual LED alert when the temperature reaches a dangerous threshold.

# Tinkercad Scheme
🔗 Project Simulation:
https://www.tinkercad.com/things/7KlkHaxx20c-tmp36-temperature-sensor-with-arduino

The Tinkercad circuit includes wiring, components, and an Arduino Uno running the temperature‑alert code.

# Components Used
This project consists of the following hardware:
| Component                                 | Quantity | Description                                         |
| ----------------------------------------- | -------- | --------------------------------------------------- |
| **Arduino Uno**                           | 1        | Main microcontroller board                          |
| **Breadboard**                            | 1        | For prototyping and wiring                          |
| **Colored LEDs**                          | 3        | Visual indicators (High / Normal / Low temperature) |
| **Resistors (220 Ω)**                     | 3        | Used in series with LEDs                            |
| **Temperature Sensor (TMP36 or similar)** | 1        | Measures ambient temperature                        |
| **Jumper Wires**                          | 8        | For connections between Arduino and breadboard      |

# Features
✔ Measures temperature in real time

✔ Displays safe, warning, or danger levels via LEDs

✔ Simple circuit—easy to build and cheap

✔ Fully simulates inside Tinkercad

✔ Ready for expansion (LCD, buzzer, WiFi, etc.)

# How It Works
The Arduino reads analog values from the temperature sensor, converts them into degrees Celsius, and activates LEDs based on thresholds:

🟢 Green LED: Normal temperature

🟡 Yellow LED: Slightly lowered temperature

🔴 Red LED: Dangerously low temperature (alert)
