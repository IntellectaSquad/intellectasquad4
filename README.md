**Smart irrigation system**

 The Smart Irrigation System leverages IoT technology to provide continuous monitoring of soil moisture, temperature, and humidity. The  aim of the Smart Irrigation System project is to develop a real-time monitoring of soil moisture, temperature, and humidity. Ultimately, the goal is to promote sustainable farming practices and conserve water resources while maximizing crop yield.

**Abstract**

The Smart Irrigation System is an advanced iot based project which continuously monitors soil moisture, temperature, and humidity using sensors.Integrated with a GSM module, the system sends real-time data and alerts via SMS directly to farmers, enabling remote monitoring and timely action.

**Area of utility**

* Enhance plant growth and health by ensuring appropriate watering schedules based on environmental conditions. 
* Continuously monitor soil moisture, temperature, and humidity levels with integrated sensors.
* Make the system cost-effective and accessible to small-scale farmers and gardeners.

  **Hardware Component**

1.Arduino uno
![image](https://github.com/user-attachments/assets/f78d7769-4660-47d4-8be6-f663142ccbc0)

2. YL 69 soil moisture sensor
  ![image](https://github.com/user-attachments/assets/953c7c6e-9f37-493d-916b-11abe0e1307d)

4. Temperature and humidity sensor
 ![image](https://github.com/user-attachments/assets/9f711590-6913-431a-900d-f78d6b721d39)

6. Gsm module
 ![image](https://github.com/user-attachments/assets/c9448fed-66d1-4e5b-a804-132c2143fbc7)

8. Lcd(Liquid crystal Display) Display
   ![image](https://github.com/user-attachments/assets/da070b6a-8df3-4095-8c34-a696c94b7ba9)


**Connections:**

1. LCD Display:
    - VCC to Arduino's 5V pin
    - GND to Arduino's GND pin
    - SDA to Arduino's A4 pin (I2C clock)
    - SCL to Arduino's A5 pin (I2C data)
2. DHT11 Sensor:
    - VCC to Arduino's 5V pin
    - GND to Arduino's GND pin
    - DATA to Arduino's digital pin 7 (defined as dht11Pin)
3. Soil Moisture Sensor:
    - VCC to Arduino's 5V pin
    - GND to Arduino's GND pin
    - ANALOG OUTPUT to Arduino's analog input pin A0 (defined as soilMoisturePin)
4. Arduino Board:
    - Connect the LCD display, DHT11 sensor, and soil moisture sensor to the corresponding pins on the Arduino board.

**Project Connections**

![image](https://github.com/user-attachments/assets/ee569e60-381b-41fa-a9d7-c2a431b41f1f)


  **Applications** 

This project "Smart irrigation system" monitors soil conditions in real-time to prevent crop failure during dry spells.It Allows farmers to monitor and manage irrigation systems from after through SMS alerts, improving response times to changing conditions. It Utilize real-time soil moisture, temperature, and humidity data to optimize irrigation schedules, reducing water usage and enhancing crop yield.
