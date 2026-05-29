Smart Light-Intensity Controller

Tinkercad Link for Simulation - https://www.tinkercad.com/things/kQ1HMmtKYiN-light-intensity-measurement-using-a-ldr-sensor?sharecode=75Z5tW3LpNI8S5WsvNj0OdZu-1ROhdt8w2VbxzQ8v2g

Welcome to the Smart Light-Intensity Controller project! This system elegantly bridges the gap between environmental sensing and automated hardware response, creating a dynamic feedback loop driven by ambient light.

🌟 Project Overview
At its core, this project demonstrates the principles of embedded systems by interpreting real-world analog signals into precise digital outputs. By utilizing a photoresistor (LDR) in a voltage divider network, the system continuously monitors its environment. As the ambient light shifts, the system reacts instantaneously, smoothly scaling the brightness of an LED to reflect the changing conditions.

🚀 Key Features
Dynamic Response: Automatically adjusts LED luminescence in real-time based on environmental light intensity.

Analog-to-Digital Precision: Seamlessly translates 10-bit analog sensor readings into an 8-bit Pulse Width Modulation (PWM) signal.

Automated Feedback Loop: Showcases foundational sensor integration concepts without requiring manual intervention.

🛠️ Hardware Architecture
This circuit is built with simplicity and efficiency in mind, utilizing standard electronic components to achieve reliable results:

Microcontroller: The brain of the operation, processing sensor data and outputting PWM signals.

Photoresistor (LDR): Acts as the primary sensor, changing resistance inversely to light exposure.

Output Indicator: A standard LED that serves as the visual representation of the system's logic.

Resistor Network: Ensures safe current limits for the LED and forms the voltage divider required for accurate analog readings.

📊 Simulation & Testing
The logic and circuitry have been thoroughly mapped and validated using digital simulation. By monitoring the output pin with a digital multimeter, one can observe the direct correlation between the simulated light input on the LDR and the proportional voltage increase driving the LED.
