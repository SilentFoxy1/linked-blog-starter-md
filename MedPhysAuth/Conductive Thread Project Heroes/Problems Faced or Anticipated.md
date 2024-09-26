
After building and testing the circuit, several challenges have arisen that need to be addressed:

1. **Sensitivity of the Conductive Thread**:
    
    - During initial testing, I manually changed the resistance by hand, which resulted in more noticeable changes in the LED brightness.
    - However, when integrated into fabric, the stretching and destretching due to natural breathing may not cause significant enough resistance changes to be detected reliably.
2. **Need for an Operational Amplifier**:
    
    - To enhance the sensitivity of the system, an **operational amplifier** (op-amp) may need to be integrated. The op-amp will amplify the small resistance changes in the conductive thread, making it easier for the Wheatstone bridge to detect variations caused by subtle chest movements during breathing.
    - Without amplification, the natural breathing might cause resistance changes that are too small to be detected reliably.
3. **Importance of Exact Resistor Values**:
    
    - Another challenge involves the use of **non-exact resistor values** in both the Wheatstone bridge and the LED circuit. For instance, I had to substitute specific resistor values by combining resistors in series or parallel, which can affect the accuracy of the measurements.
    - In the LED circuit, where exact current-limiting resistors are crucial for the proper brightness control, I used a combination of resistors (150 ohms and 240 ohms) in series due to the unavailability of the exact required values. This improvisation could lead to inconsistent brightness or incorrect readings from the sensor.
    - Moving forward, sourcing the exact resistor values will be important to ensure the circuit functions as designed, especially for the Wheatstone bridge, where precise balancing of resistance is necessary to detect small changes reliably.

Addressing these issues, especially incorporating an operational amplifier and using exact resistor values, will be key to ensuring the system functions accurately and can monitor breathing patterns in a real-world setting.