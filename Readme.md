
# ESP32 WiFi Dynamic Connection Project

This project demonstrates how to dynamically connect an ESP32 to WiFi using a web server for WiFi selection. Users can easily configure and connect the ESP32 to their preferred WiFi network through a simple web interface.

## Features

- Dynamic WiFi connection: Allows the ESP32 to connect to any WiFi network without hardcoding credentials.
- Web server: Provides a user-friendly web interface for selecting and configuring WiFi settings.
- Easy setup: Minimal configuration required, making it user-friendly for beginners.

## Getting Started

### Prerequisites

- [Arduino IDE](https://www.arduino.cc/en/software) installed.
- [ESP32 board support](https://github.com/espressif/arduino-esp32#installation-instructions) added to the Arduino IDE.

### Installation

1. Clone or download this repository to your local machine.

2. file wifi_element contains the code 

3. Set up your ESP32 board in the Arduino IDE.

4. Upload the sketch to your ESP32.


###Usage

Power up your ESP32 and open the Serial Monitor in the Arduino IDE.

The ESP32 will create a WiFi network named "NEWTEST_AP." Connect your device to this network.

Open a web browser and navigate to http://192.168.4.1.

You will be presented with a simple web page to enter your WiFi credentials.

After entering the credentials, click "Connect."

The ESP32 will attempt to connect to the specified WiFi network. The status will be displayed on the web page and in the Serial Monitor.

Once connected, the ESP32 will continue to run your main application

##Acknowledgments

This project was inspired by the need for a simple and user-friendly way to connect an ESP32 to WiFi dynamically.

Feel free to customize the sections, links, and instructions based on your specific project details.
