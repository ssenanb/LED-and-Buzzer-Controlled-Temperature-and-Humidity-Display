# LED-and-Buzzer-Controlled-Temperature-and-Humidity-Display

->Description

This project implements a temperature and humidity monitoring system using an STM32 microcontroller and a DHT11 sensor. The system performs the following tasks:

Monitors the temperature and humidity values from the DHT11 sensor.

Turns on an LED if the temperature is below 30°C.

Activates a buzzer if the humidity drops below 50%.

Turns off both the LED and buzzer when the temperature and humidity are within the normal range.

This system is built using STM32 HAL libraries and is ideal for applications that require environmental monitoring with basic thresholds.

->Components Used

STM32F0 Microcontroller


DHT11 Temperature and Humidity Sensor

LED

Buzzer

-> Circuit Installation 

<img src="https://github.com/ssenanb/LED-and-Buzzer-Controlled-Temperature-and-Humidity-Display/blob/main/circuit-installation-2.jpeg?raw=true" alt="Devre Kurulumu 2" width="500"/>

->Features

LED Control: Lights up when the temperature is less than or equal to 30°C.

Buzzer Control: Activates when the humidity is less than or equal to 50%.

->Hardware Setup

Connect the DHT11 sensor to the STM32 microcontroller as follows:

DHT11 Data Pin -> PA1

VCC -> 3.3V

GND -> Ground

Connect an LED to PA0 (with a current-limiting resistor).

Connect a buzzer to PA2.

-> I used this library : https://github.com/quen0n/DHT11-DHT22-STM32-HAL
