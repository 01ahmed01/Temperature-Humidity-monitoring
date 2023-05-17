# Temperature-Humidity-monitoring
Group 10

# Group members:
1.	Ahmed Mohamed Mostafa
2.	Mohammed Tamim Bakrou 
3.	Wahab 

# 1.0	Problem statement 
Indoors Temperature and humidity have negative effects if not controlled or balance in a specific range. Unmonitored humidity and temperature levels can affect different aspects in an indoor setting. These effects can range from damage of property to detrimental health risks.

There is a “sweet spot” when it comes to balancing humidity and temperature levels. The ideal range of temperature is between 20 to 25 Celsius and for humidity between 30% to 50%, Going below or above these ranges can create an indoor environment that is not healthy and can damage the property. 

For example, High humidity levels will cause growth of mold and mildew, damage paintings, peel wallpapers, and damage walls. Low humidity levels, on the other hand, can cause dry and itchy eyes, dry skin, and an increase in rate of infections.

Therefore, monitoring indoor temperature and humidity is crucial to create a healthy indoor environment. By creating an IoT monitoring system we can monitor Temperature and humidity levels so we can better control the climate of the indoor environment and attempt to keep the levels in the ideal range.  

# 2.0 System Architecture
The IoT system will be divided into three main parts:
•	Sensor and device 
•	Cloud Platform using Django rest framework and python everywhere 
•	Dashboard
![image](https://github.com/01ahmed01/Temperature-Humidity-monitoring/assets/129277661/f0e4bcf2-6d81-407d-bf6b-0d639f503c42)

# 3.0	Sensors 

ESP32

![image](https://github.com/01ahmed01/Temperature-Humidity-monitoring/assets/129277661/ccc69160-da65-4cff-88a3-7317f6b6c839)

Temperature and Humidity sensor [DHT22]

![image](https://github.com/01ahmed01/Temperature-Humidity-monitoring/assets/129277661/378a6a34-378c-4a92-9e51-40314dcf565f)

Overview of sensor

![image](https://github.com/01ahmed01/Temperature-Humidity-monitoring/assets/129277661/e4639233-8ce0-413c-a8e9-d47cfab123f6)

# 4.0 Cloud platform 
A cloud platform is needed to connect the hardware with the user’s smartphone device. The cloud platform should be updated in real time as Temperature and humidity levels change. Data from the cloud platform should be presented on the dashboard for users to view. The server is created using Django with pythonanywhere host. A unique server is created using Ubuntu. We push the project files onto Github so all group members can edit and contribute

# 5.0 Dashboard 
The dashboard is connected to the ESP32 senor and displays 3 variables to the user: Temperature, Humidity, and fire. Each variable will be plotted as they change over time, giving the user easy to understand info about the climate of their indoor environment. In case the temperature rises to dangerously high levels, an alarm will be activated and the fire status will display “true”. 

![image](https://github.com/01ahmed01/Temperature-Humidity-monitoring/assets/129277661/5b169d34-6243-4342-bcb2-4a40d5f83c96)
