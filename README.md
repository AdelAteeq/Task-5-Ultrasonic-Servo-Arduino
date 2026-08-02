# Task 5 - Ultrasonic Servo Arduino

## Description

Control a Servo Motor using an HC-SR04 Ultrasonic Sensor and Arduino. The servo rotates to a specific angle when an object is detected within 10 cm and returns to its original position when the object moves away. Different angles and distances were tested, with an LED added to indicate obstacle detection.

## Components

- Arduino Uno
- HC-SR04 Ultrasonic Sensor
- Servo Motor
- LED
- 220Ω Resistor
- Jumper Wires
- Breadboard

## Wiring

### Ultrasonic Sensor

| HC-SR04 | Arduino |
|---|---|
| VCC | 5V |
| GND | GND |
| TRIG | D9 |
| ECHO | D10 |

### Servo Motor

| Servo | Arduino |
|---|---|
| Signal | D6 |
| VCC | 5V |
| GND | GND |

### LED

| LED | Arduino |
|---|---|
| Anode | D7 through 220Ω resistor |
| Cathode | GND |

## How It Works

- If the detected distance is 10 cm or less, the servo rotates to 90° and the LED turns ON.
- If the distance is greater than 10 cm, the servo returns to 0° and the LED turns OFF.

## Experiments

The following values were tested:

- Servo angle: 90°
- Servo angle: 45°
- Servo angle: 180°
- Detection distance: 10 cm
- Detection distance: 15 cm

## Problems and Solutions

During the simulation, an incorrect LED and power connection caused a problem with the Arduino. The wiring was checked and corrected by ensuring proper connections between 5V, GND, the servo, ultrasonic sensor, LED, and resistor.

## Result

The system successfully detects objects using the HC-SR04 Ultrasonic Sensor and controls the Servo Motor according to the detected distance. The LED also indicates when an obstacle is detected.

## Project Link

[Tinkercad Project](PASTE_YOUR_TINKERCAD_LINK_HERE)
