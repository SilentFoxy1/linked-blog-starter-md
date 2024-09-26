In the "Heroes" project at the MedPhys AUTH research lab, a system is being developed to monitor a patient's breathing using a jacket embedded with conductive thread. The conductive thread, sewn into the jacket, detects changes in resistance as the patient's chest expands and contracts during breathing. These resistance changes are measured using a Wheatstone bridge circuit, which includes three 100-ohm resistors and a variable resistor (70-120 ohms).

The sensor output is processed by an **Arduino Mega**, which reads the analog data and controls the brightness of an LED, providing a visual representation of the breathing pattern. As the sensor values change with the patient's breathing, the LED dims or brightens accordingly.

The circuit was designed using **[[KiCad]]**, a popular open-source software for electronic design automation (EDA), which allowed for precise planning of the components and wiring involved.

**Key Components:**

- **Conductive Thread**: Sewn into the jacket to monitor chest movements during breathing.
- **Wheatstone Bridge Circuit**: Detects small changes in resistance.
- **Arduino Mega**: Processes the sensor data and controls the LED.
- **LED**: Visualizes the breathing pattern by adjusting brightness.
- **[[#KiCad schematic for Conductive Thread]]** : Used for designing the circuit layout.

This system offers a wearable, non-invasive solution for monitoring a patient’s respiratory activity.