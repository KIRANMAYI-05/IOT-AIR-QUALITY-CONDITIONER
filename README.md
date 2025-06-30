# IOT-AIR-QUALITY-CONDITIONER

COMPANY : CODTECH IT SOLUTIONS

NAME : KOMPELLA KIRANMAYI

INTERN ID : CTO4DF1700

DOMAIN : INTERNET OF THINGS

DURATION : 4 WEEKS

MENTOR : NELLA SANTOSH KUMAR

DESCRIPTION:

🔍 IoT Air Quality Monitor – Detailed Description
The IoT Air Quality Monitor is a basic yet essential prototype designed to monitor air pollution or gas levels in an environment using an Arduino Uno and a gas sensor (such as the MQ-2 or MQ-135). This system can be used in homes, industries, laboratories, or urban areas to provide real-time air quality information and trigger alerts in case of harmful gas presence. It is a fundamental part of smart city and IoT applications.

In this task, we utilized Tinkercad, a free online simulator developed by Autodesk that allows you to design, build, and simulate electronic circuits and Arduino codes without physical hardware. This is especially useful for students, hobbyists, or anyone doing internships or academic projects remotely.

🧰 Components Used
Here are the main components used in the IoT Air Quality Monitor circuit:

Arduino Uno

Acts as the microcontroller to process and read sensor data.

It is programmed using Arduino C/C++.

MQ Gas Sensor (e.g., MQ-2 or MQ-135)

Detects gases like smoke, methane, propane, alcohol, and CO2.

Outputs analog voltage based on gas concentration.

Jumper Wires

Used to make electrical connections between the components on the breadboard and the Arduino.

Tinkercad Software (Online)

Used to create the circuit diagram.

Simulates sensor readings and runs the Arduino code.

Provides a Serial Monitor to display outputs without needing real-world devices.

🛠️ Circuit Connections (as per Tinkercad simulation)
The connection setup on the Tinkercad virtual breadboard is simple:

Gas Sensor Connections:

VCC of the sensor → Connect to 5V pin of Arduino.

GND of the sensor → Connect to GND on Arduino.

AOUT (Analog Out) → Connect to A0 analog pin on Arduino.

Arduino USB Port:

Used virtually in Tinkercad to power the Arduino and upload the code.

In a real-world scenario, it would connect to a computer or power bank.

💻 How We Used Tinkercad in the Task
Tinkercad played a central role in this project. Here's how:

We designed the entire circuit diagram on the virtual breadboard in Tinkercad, mimicking real-life physical connections.

The gas sensor was virtually connected to the Arduino Uno using jumper wires by dragging and dropping components.

Tinkercad allows you to write and upload code directly into the Arduino IDE simulation. The code used reads analog values from the sensor and displays them in the Serial Monitor, helping us observe changing gas levels in real-time.

Tinkercad simulates the analog input values for the gas sensor even though no actual gas is present. It generates sample fluctuating values which help in testing.

By using this platform, we avoided the need for physical components, which is useful for internships or learning remotely.

📈 Working of the Project
Once the simulation starts:

The Arduino reads the analog voltage coming from the gas sensor through pin A0.

This voltage corresponds to the concentration of gas in the surrounding air.

The code processes this data and prints it to the Serial Monitor every second.

You can adjust the threshold and later extend the project to trigger alarms, LEDs, or IoT platforms (like Blynk/Thingspeak) when pollution exceeds safe limits.

🌐 Applications of This Project
Air pollution monitoring in cities.

Smoke detection in homes or industries.

Toxic gas monitoring in labs.

Real-time IoT integration with mobile apps or dashboards.

✅ Conclusion
The IoT Air Quality Monitor is a simple yet highly impactful project to start exploring IoT concepts. With Tinkercad, we were able to simulate this task completely in a virtual environment, making it ideal for learning and prototyping. By combining basic electronics knowledge with virtual tools, we gain hands-on experience in building smart, environment-focused systems.
