# IR Obstacle Detection Sensor Module

A simple IR (Infrared) Obstacle Detection Sensor Module designed using discrete electronic components. The circuit uses an IR LED to emit infrared light and a photodiode to detect reflected IR rays. An LM358 operational amplifier configured as a comparator determines whether an obstacle is present based on the reflected signal.

This project demonstrates the working principle behind commonly available IR obstacle sensor modules and is suitable for beginners learning analog electronics and sensor interfacing.

---

## Features

- Infrared obstacle detection
- Adjustable detection sensitivity using a potentiometer
- LM358 comparator-based signal processing
- Visual output indication using an LED
- Simple and low-cost design
- Suitable for Arduino and other microcontrollers

---

## Components Used

| Component | Quantity |
|-----------|---------:|
| IR LED | 1 |
| Photodiode | 1 |
| LM358 Op-Amp | 1 |
| 10kΩ Potentiometer | 1 |
| 150Ω Resistor | 1 |
| 220Ω Resistor | 1 |
| 10kΩ Resistor | 1 |
| LED Indicator | 1 |
| 5V Power Supply | 1 |

---

## Working Principle

1. The IR LED continuously emits infrared light.
2. When an object comes in front of the sensor, the emitted IR light reflects back.
3. The photodiode detects the reflected infrared light and generates a corresponding voltage.
4. The LM358 compares this voltage with a reference voltage set by the potentiometer.
5. If the detected signal exceeds the reference level, the comparator output changes state.
6. The output LED indicates whether an obstacle has been detected.

---


## Applications

- Obstacle detection robots
- Line-following robots
- Autonomous vehicles
- Industrial object detection
- Automatic door systems
- Distance sensing experiments
- Educational electronics projects

---

## Learning Outcomes

- IR sensing fundamentals
- Photodiode operation
- Comparator circuits
- LM358 Op-Amp applications
- Analog signal processing
- Adjustable threshold detection
- Electronic circuit design

---

## Future Improvements

- Add digital output pin for Arduino interfacing
- Include buzzer indication
- Improve sensing range
- Design a custom PCB
- Add power indicator LED

---

## Author

Janani M

Electronics and Communication Engineering (ECE)
