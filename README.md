# -IoT-Based-Gas-Detection-and-Alarm-System
🚀 Overview
----------------------------------------------------------------------------------------
This project is an IoT-based gas leakage detection system built using an Arduino Uno, gas sensor (MQ series), buzzer, and LCD display. The system continuously monitors air quality for the presence of harmful gases (like LPG, methane, or smoke), and triggers an alarm and LCD warning when dangerous levels are detected.

It simulates a real-world safety device suitable for smart homes, industrial safety, or kitchen monitoring.

-----------------------------------------------------------------------------------------------------------------------------------

🧰 Tech Stack
-----------------------------------------------------------------------------------------------------------
Arduino Uno

MQ Gas Sensor (MQ-2 / MQ-135)

16x2 LCD Display

Buzzer

Tinkercad Circuits (Simulation)

C++ (Arduino IDE)

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

⚙️ Features
-----------------------------------------------------------------------------------------------------------------------
🔍 Real-time gas monitoring

📟 Live display of gas values on LCD

🚨 Alarm trigger when threshold is exceeded

🔌 Easy to simulate on Tinkercad

💬 Serial monitor output for debugging/logging

---------------------------------------------------------------------------------------------------------------------------------------------------------

🛠️ Circuit Components & Wiring
--------------------------------------------------------------------------------------------------------------------
| Component     | Arduino Pin    |
| ------------- | -------------- |
| MQ Gas Sensor | A0             |
| Buzzer        | D8             |
| LCD RS        | D12            |
| LCD EN        | D11            |
| LCD D4-D7     | D5, D4, D3, D2 |

✅ Main Components:

Arduino Uno

Gas Sensor Module (likely MQ-2)

16x2 LCD Display

Red and Green LEDs (with 330Ω resistors)

Buzzer (in code, not visible in schematic but likely connected to D8)

Pull-down resistor (4kΩ) possibly used for signal stabilization


[gas sensor .pdf](https://github.com/user-attachments/files/21142951/gas.sensor.pdf)

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------

📷 Screenshots
--------------------------------------------------------------------------------------------------------------------

![Screenshot 2025-07-09 174847](https://github.com/user-attachments/assets/f834a723-7a27-41cd-86c8-90648aacf149)

![Screenshot 2025-07-09 175015](https://github.com/user-attachments/assets/e4582b88-b8f1-4c92-88cd-592a0482ca1c)

![Screenshot 2025-07-09 175110](https://github.com/user-attachments/assets/ab13ce92-6c98-4be4-9925-60d6322dc658)

![Screenshot 2025-07-09 175436](https://github.com/user-attachments/assets/027f899e-4e82-4962-a9d8-f3cb9d2ea8aa)

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

🔗 Tinkercad Simulation
----------------------------------------------------------------------------------------------
You can view and run the simulation online:

👉 Tinkercad Project Link:https://www.tinkercad.com/things/jgrNn1fMxRZ-gas-sensor-?sharecode=4stIEXM82L7iiiDfLeRjr8bETaZrV8uNcfLyq0h_TA8


