# Mini Temperature Controller (Arduino / Wokwi)

## Description
Project Arduino simulation of a mini temperature controller with:
- Potentiometer as temperature input
- Fan LEDs (LOW / MEDIUM / HIGH)
- Alarm LED / Buzzer

Simulation done in [Wokwi](https://wokwi.com/).

---

## Components
- Arduino Uno
- Potentiometer
- LED x3 (Fan LOW, MEDIUM, HIGH)
- Buzzer / Red LED (Alarm)
- 220Ω resistors

---

## Wiring Diagram
![Wiring Diagram](images/wiring_diagram.png)

---

## How it Works
| Temperature | Fan LEDs         | Alarm |
|------------|-----------------|-------|
| 0–49       | OFF             | OFF   |
| 50–79      | LOW             | OFF   |
| 80–99      | LOW + MED       | OFF   |
| ≥100       | LOW + MED + HIGH| OFF   |
| ≥90        | see above       | ON    |

---

## Simulation Screenshots
- Low Temp: ![Low Temp](images/screenshot_low_temp.png)
- High Temp: ![High Temp](images/screenshot_high_temp.png)

---

## Video
[Simulation Video](video/simulation.mp4)

---

## Skills Demonstrated
- Arduino programming (C++)
- Analog input / PWM logic
- Simulation with Wokwi
- Embedded system logic
- Portfolio-ready documentation
