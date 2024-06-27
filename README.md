# IOT-MIN_IPROJECT


	ABSTRACT
This project introduces an innovative solution aimed at elevating the convenience, energy efficiency, and environmental awareness within contemporary homes. By harnessing the power of Internet of Things (IoT) technology, the system seamlessly integrates two essential sensors – the Light Dependent Resistor (LDR) and the DHT11 temperature and humidity sensor – to establish a sophisticated and automated home environment.
Key objectives of the project encompass:

• Intelligent Light Control: The LDR sensor adeptly discerns ambient light levels, facilitating automatic adjustment of indoor lighting. Through a meticulous analysis of light intensity, the system optimizes artificial lighting, curtains, and blinds to enhance energy efficiency and cultivate a comfortable living space.

• Real-time Climate Management: The DHT11 sensor continually monitors temperature and humidity conditions, enabling precise climate control. The system dynamically adjusts Heating, Ventilation, and Air Conditioning (HVAC) systems to sustain an optimal indoor environment, prioritizing the occupants' comfort and well-being.

• Seamless IoT Connectivity: The sensors seamlessly connect to an IoT platform, enabling remote monitoring and control via a user-friendly mobile application or web interface. This empowers users to conveniently access and regulate their home settings from any location, fostering an unprecedented level of convenience and control.

• Insightful Data Analysis: The project features a robust data analytics component, aggregating sensor data over time. Through thorough analysis of historical data, the system provides valuable insights into energy consumption patterns, preferences related to light and temperature, and identifies potential energy-saving opportunities.

The proposed smart home automation system offers numerous advantages, including heightened energy efficiency, reduced utility costs, and an enhanced overall quality of life. Moreover, it actively contributes to a more sustainable and eco-friendly living environment by minimizing energy wastage.

This endeavor exemplifies the transformative potential of IoT technology in converting traditional homes into intelligent, adaptive living spaces. Through the integration of LDR and DHT11 sensors, users can embrace a lifestyle that is not only more comfortable and efficient but also environmentally conscious. The incorporation of data-driven insights further amplifies the potential for a truly enhanced smart home experience.

TABLE OF CONTENTS
                                                               1. Introduction
In the ever-evolving landscape of technology, the concept of a "smart home" has gained significant traction. The emergence of the Internet of Things (IoT) has transformed homes from mere physical spaces into interconnected ecosystems of devices and sensors, designed to elevate convenience, energy efficiency, and security. Our project, titled "IoT-Based Smart Home Automation with LDR and DHT11 Sensors," fully embraces this technological transformation by creating an intelligent and automated living environment.

The primary aim of our project is to seamlessly integrate two vital sensors into a sophisticated home automation system: the Light Dependent Resistor (LDR) and the DHT11 temperature and humidity sensor. Serving as the eyes and senses of the smart home, these sensors continuously collect data about the environment, enabling the system to respond in real-time to changing conditions.

The LDR sensor, monitoring ambient light levels, empowers the system to make informed decisions about lighting control, adjusting artificial lighting according to the occupants' requirements. This not only optimizes energy usage but also contributes to the creation of a more comfortable and energy-efficient living space. Additionally, the DHT11 sensor continually measures temperature and humidity, facilitating precise climate control. The system adapts heating, ventilation, and air conditioning (HVAC) systems to maintain an ideal indoor environment, enhancing the well-being of the occupants.

Crucially, these sensors are not isolated; instead, they are interconnected through an IoT platform. This connectivity enables users to remotely monitor and control their smart home through a user-friendly mobile application or web interface. Whether at home or away, homeowners can adjust lighting, temperature, and humidity settings, providing unparalleled convenience and control.
Moreover, our project incorporates a data analysis component to collect and analyze sensor data over time. This feature yields insights into energy consumption patterns, lighting preferences, and potential energy-saving opportunities, empowering users to make informed decisions about their home environment.
                                                                    
 The "IoT-Based Smart Home Automation with LDR and DHT11 Sensors" project brings numerous advantages, including heightened energy efficiency, reduced utility costs, and an enhanced quality of life. Additionally, it actively contributes to a more sustainable and eco-friendly living environment by minimizing energy wastage and improving the overall living experience.

This project underscores the transformative potential of IoT technology in converting conventional homes into adaptive, intelligent living spaces. Through the integration of LDR and DHT11 sensors, users can embrace a lifestyle that is not only more comfortable and efficient but also environmentally conscious, leveraging the insights derived from data-driven analysis to further optimize their smart home experience.

                                                     2.	Components and Modules
In this section, various components and Modules being used for IoT based SMART HOME AUTOMATION development is discussed:
  2.1 ESP 32
   The ESP32 is a powerful microcontroller developed by Espressif Systems, offering dual-core             processing, integrated Wi-Fi and Bluetooth connectivity, and a rich set of peripherals. This microcontroller is widely used in IoT projects, wearables, and industrial applications due to its low power consumption, secure features, and active developer community.
                        
 
2.2 DHT11 sensor
The DHT11 is a cost-effective temperature and humidity sensor frequently used in electronics 
projects. It provides accurate readings within a specific range, making it suitable for climate control in home automation, weather stations, and environmental monitoring. With a simple digital interface, it's easy to use with microcontrollers and Arduino boards, making it popular in DIY applications.
 
Figure 2 : DHT11 sensor
2.3 LDR sensor
The Light Dependent Resistor (LDR), also known as a photoresistor, is a passive electronic component that changes its resistance in response to varying light levels. As light intensity increases, the resistance decreases. LDRs are commonly used in light-sensing applications, such as streetlights, cameras, and automatic lighting systems. They are cost-effective and easy to interface with microcontrollers, making them a popular choice for projects requiring light detection and control.
 
Figure 3 :LDR sensor
4
3.Circuit description & working principle
Designing a smart home automation project incorporating an LDR (Light Dependent Resistor), DHT11 sensor (for temperature and humidity monitoring), and an LED for Internet of Things (IoT) integration involves the utilization of various components and adhering to fundamental principles. The following outlines the working principles and essential steps for the implementation of such a project:

1. Hardware Configuration:
   LDR (Light Dependent Resistor): The LDR gauges the ambient light level. Its resistance decreases in the presence of light and increases in darkness.
 DHT11 Sensor:Used for temperature and humidity measurement, the DHT11 provides digital output for these parameters.
 LED: The LED functions as an output device, serving purposes such as indicating system status or controlling connected home appliances.
   Microcontroller (e.g., Arduino or Raspberry Pi): Serving as the system's core, the microcontroller interconnects the sensors and the LED.

2. Sensor Data Acquisition:
   - The microcontroller reads data from the LDR to assess the ambient light level. This data can be processed for various applications, such as activating lights in low-light conditions or managing window blinds.
   - The DHT11 sensor supplies data on temperature and humidity. This information facilitates climate control and automation, such as activating a fan in response to temperature changes.

3. Internet of Things (IoT) Integration:
   - To connect the system to the internet, a Wi-Fi module or Ethernet shield is necessary for the microcontroller. Examples include using an ESP8266 for Arduino or a Raspberry Pi with built-in Wi-Fi.
   - Utilize an IoT platform or service (e.g., Blynk, ThingSpeak, Adafruit IO) to transmit sensor data to the cloud. Configure the microcontroller to regularly send data intervals.

By adhering to these principles, a smart home automation system employing LDR and DHT11 sensors, coupled with an LED for IoT integration, can be developed. This system offers convenience, energy efficiency, and the capability to monitor and control your home remotely.


4.Algorithms & flowchart
4.1	Algorithm :
The algorithm of overall process:-
Step 1: Start the process
 step 2: connected to wifi
Step 3: Read temerature and humidity
Step 4: Get temperature and humidity values from anolog pins 
Step 5: Send data to Blynk
Step 6: Delay to 10 seconds
Step 7: Turn on and off led lights using blynk interface
Step 8: End
6
  4.2.Flowchart:


Figure 5: Flowchart for overall process


5.Implementation
Implementation includes hardware as well as software connections
•	Hardware implementations:
It involves connection of  DHT 11 and LDR sensors to respective pins of  ESP 32.
•	Software implementations:
It involves implementation of code and connecting it to blynk interface.
Code:
#define BLYNK_PRINT Serial
#define BLYNK_TEMPLATE_ID "TMPL3ipIs2nB9"
#define BLYNK_TEMPLATE_NAME "smart home"
#define BLYNK_AUTH_TOKEN "bSwPpp-RQ28IqjeCkBMYjxKWK6cRFVMG"

#include <WiFi.h>
#include <WiFiClient.h>
7
#include <BlynkSimpleEsp32.h>
#include <DHT.h>
// Your WiFi credentials.
char ssid[] = "POCO";
char pass[] = "12345678";
BlynkTimer timer;
//sensor pins
#define DHTPIN 27
#define DHTTYPE DHT11
DHT dht(DHTPIN,DHTTYPE);
#define LDR_PIN 34
//virtual pins
#define VPIN_TEMPERATURE V0
#define VPIN_HUMIDITY V1
#define VPIN_LDR V2
float temperature1 = 0;
float humidity1   = 0;
float ldrVal = 0;
void readSensor() {
  ldrVal = map(analogRead(LDR_PIN), 400, 4200, 0, 100);
  Serial.print("LDR - "); Serial.println(ldrVal);
  float h = dht.readHumidity();
  float t = dht.readTemperature();
  if (isnan(h) || isnan(t)) {
    Serial.println("Failed to read from DHT sensor!");
    return;
  }
  else {
    humidity1 = h;
    temperature1 = t;
    Serial.print("Temperature - "); Serial.println(t);
    Serial.print("Humidity - "); Serial.println(h);
  }
}


void sendSensor()
{
  readSensor();
  Blynk.virtualWrite(VPIN_TEMPERATURE, temperature1);
  Blynk.virtualWrite(VPIN_HUMIDITY, humidity1);
  Blynk.virtualWrite(VPIN_LDR, ldrVal);
}

void setup()
{
  Serial.begin(115200);
8
  Blynk.begin(BLYNK_AUTH_TOKEN, ssid, pass);
  dht.begin();
  timer.setInterval(1000L, sendSensor);
}

void loop()
{
  Blynk.run();
  timer.run();
}

6. Result
 
Figure 6: Blynk interface providing details on humidity ,temperature and light intensity

7.	Conclusion
In conclusion, the smart home automation project integrating an LDR (Light Dependent Resistor), DHT11 sensor, and LED for Internet of Things (IoT) offers a practical and versatile solution for enhancing home convenience, energy efficiency, and remote monitoring and control. Here are some key takeaways:

9
-	Environmental Monitoring: The project provides the ability to monitor and react to changes in environmental conditions within your home. The DHT11 sensor allows you to keep track of temperature and humidity, enabling climate control and automation.
-	Light Sensing: The LDR sensor enables the system to respond to changes in ambient light levels. For example, you can automatically turn on lights when it gets dark or adjust window blinds to regulate natural light.
-	IoT Connectivity:By incorporating Wi-Fi capabilities, such as an ESP32, the project connects your smart home system to the internet. This connectivity empowers remote monitoring and control, enabling you to access real-time data and manage your home from anywhere via a mobile app or web interface4. Automation and Alerts:With the IoT platform and sensor data, you can create automation rules and receive alerts. For instance, you can set up alerts for extreme temperature or humidity levels, allowing you to take appropriate action5. Energy Efficiency: The project supports energy-efficient practices by automatically turning off lights when there is sufficient ambient light and by controlling heating or cooling systems based on temperature and humidity.
-	Security: The system can enhance home security by controlling lighting or other devices remotely, giving the illusion of an occupied home while you're away.
-	Customization: You can customize the project to suit your specific needs and preferences. Implement additional sensors, integrate voice control, or create more complex automation routines as your requirements evolve.
-	Safety and Reliability: Ensure that the system is implemented with safety and security in mind, especially when controlling appliances remotely.

