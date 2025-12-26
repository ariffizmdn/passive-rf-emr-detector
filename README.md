# passive-rf-emr-detector
# Passive Radio Frequency Electromagnetic Radiation Monitor

Simple low-cost RF/EMF detector built for **Electromagnetic Fields and Waves** course project.

## What It Does
Detects RF signals from:
- Mobile phones (600 MHz – 3.8 GHz)
- Wi-Fi routers (2.4 GHz & 5 GHz)
- Bluetooth, microwave leakage, hidden cameras, etc.

Gives instant visual (LED) + audible (buzzer) alert when RF is present.

## How It Works
- Antenna → 2× 1N34A germanium diodes (voltage doubler)
- LM358 op-amp (high-gain amplifier + comparator)
- Powered by 9 V battery

## Files in This Repo
- Schematic diagram
- hardware
- rf-detector-demo .mp4

## Quick Test Results
| Source            | LED              | Buzzer         |
|-------------------|------------------|----------------|
| Wi-Fi Router      | Bright           | Continuous     |
| Mobile Phone      | Blinking         | Intermittent   |
| Wall Socket       | Bright           | Continuous     |
| Water Heater      | Bright           | Continuous     |

Feel free to clone, build, or improve it!  
Great for learning RF basics or checking for hidden transmitters.

---
*Open source for educational use*
