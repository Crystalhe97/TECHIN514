## TECHIN514 
# Bath Quality Monitor
- The product is designed for families who enjoy bathing. 
- This product can detect inner water temperature and turbidity.
- Allowing users to easily adjust the water temperature (avoiding initially setting the temperature too hot or too cold; needing to add more hot water after one family member has bathed and another wishes to bathe later).
- Alert users if they need to change the water.
- This product allows each family member to have a comfortable bathing experience at their preferred water temperature, saving time (avoiding repeatedly adjusting water temperature or waiting for overly hot water to cool down) and saving water resources (preventing the need to drain some water if the temperature is not right despite the tub being full).
![Color Analyzer 1](https://github.com/Crystalhe97/TECHIN514/blob/main/1.jpg?raw=true)

# Sensor Device
## Microcontroller: ESP32
## DS18B20 Digital Temperature Sensor (Waterproof)
- Datasheet https://www.analog.com/media/en/technical-documentation/data-sheets/ds18b20.pdf
- The DS18B20 is a widely used electronic component for temperature measurement 
- The DS18B20 communicates over a one-wire bus that requires only one data line (and ground) for communication 
- The DS18B20 provides temperature readings in a digital format (incorporates an analog-to-digital converter) and other signal processing circuitry to output temperature data in a digital form
## TSW-10 Turbidity Sensor 
- Datasheet https://files.seeedstudio.com/products/101020752/Turbidity%20Sensor%20specification.pdf 
- The TSW-10 uses an optical method to measure turbidity. It shines an LED through the water and measures how much light is scattered by the suspended particles in the water.
- The turbidity is usually measured in Nephelometric Turbidity Units (NTU). Higher NTU values indicate higher turbidity, which means there are more particles suspended in the water.
- The sensor usually provides an analog with the turbidity level. This output can be connected to a microcontroller or data logger for recording and analysis.
![Color Analyzer 1](https://github.com/Crystalhe97/TECHIN514/blob/main/2.jpg?raw=true)
- The two sensors are connected to ESP32. 
- Using the Turbidity Sensor to monitor if the water is clear
- Using the Temperature Sensor to monitor the inner water temp
- Using a battery to get power
- Include a button/switch to turn on and turn off the device

# Display Device
## Microcontroller: ESP32
## OLED
- Displaying the water temperature and turbidity.
- Helping users to know if the bath water is comfortable, hot, or cold. 
- Helping users rely on the display data to adjust the bath water temperature
## Stepper-motor-driven gauge needle 
- According to the turbidity, indicate if the water is clear, normal, or dirty.
## LED
- If the turbidity is higher than the figure, the LED light s up and alerts users to change the bath water. If the water is dirty.
![Color Analyzer 1](https://github.com/Crystalhe97/TECHIN514/blob/main/3.jpg?raw=true)

# Figure
## How the devices communicate with each other
![Color Analyzer 1](https://github.com/Crystalhe97/TECHIN514/blob/main/4.jpg?raw=true)

## Work Flow
![Color Analyzer 1](https://github.com/Crystalhe97/TECHIN514/blob/main/6.jpg?raw=true)
