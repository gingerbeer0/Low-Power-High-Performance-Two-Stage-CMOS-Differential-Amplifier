# Low-Power High-Performance Two-Stage CMOS Differential Amplifier

This project implements a two-stage CMOS differential amplifier designed and simulated using PSpice. The amplifier meets strict performance targets in gain, bandwidth, and power efficiency, making it suitable for analog signal processing systems requiring both high performance and low power consumption.

## Description
The amplifier was designed to achieve high open-loop gain, wide gain-bandwidth product, and fast slew rate, all while keeping the power under 3 mW. Special attention was given to the trade-off between frequency stability and speed by optimizing compensation techniques (Miller capacitor with series resistor). Layout and schematic were completed in Virtuoso, followed by extensive AC, transient, and DC analysis.

## Key Specifications
| Parameter       | Value         |
|----------------|---------------|
| VDD            | 2.5 V         |
| Open-loop Gain | 86.355 dB     |
| GBW            | 31.943 MHz    |
| Phase Margin   | 61.174°       |
| Slew Rate      | 50 V/μs       |
| Output Swing   | 2.5 V_peak-to-peak |
| Power          | 2.865 mW      |
| Load           | R₁ = 1.5 kΩ, C₁ = 10 pF |
| VCM            | 0.5 V         |

## Tools Used
- PSpice

## Features
- Fully differential input stage with current mirror biasing
- Common-source second stage for high output swing
- Miller compensation with R-C zero shifting
- Meets all design specs: Gain, GBW, PM, SR, and Power

## Screenshots
> Add here:
![image](https://github.com/user-attachments/assets/85bf5b3f-5fd5-48c2-9535-884f93acf186)
![image](https://github.com/user-attachments/assets/3585d7ab-237d-4df6-9d28-449416139208)
![image](https://github.com/user-attachments/assets/d4b72f7b-0232-4021-92da-2765bede2d7d)
![image](https://github.com/user-attachments/assets/46afe304-3655-4e9d-b472-6bd0397ac32f)
![image](https://github.com/user-attachments/assets/68c784e8-5c91-4e48-924b-88560c7be0af)
