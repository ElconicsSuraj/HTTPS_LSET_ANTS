

# ESP8266 HTTP POST Example

This Arduino sketch demonstrates how to send HTTP POST requests with JSON data using an ESP8266 microcontroller. It can be used to send sensor data to a server or API that accepts JSON payloads.

## Prerequisites

Before using this code, make sure you have the following:

- An ESP8266 board (e.g., NodeMCU, Wemos D1 Mini).
- Arduino IDE installed on your computer.
- The necessary libraries installed (see Dependencies section).

## Dependencies

This project relies on the following libraries, which you should install using the Arduino Library Manager:

- [ESP8266WiFi](https://github.com/esp8266/Arduino) - Provides Wi-Fi connectivity for the ESP8266.
- [ESP8266HTTPClient](https://github.com/esp8266/Arduino) - Allows you to send HTTP requests and handle responses.
- [ArduinoJson](https://arduinojson.org/) - Used for creating and parsing JSON data.

## Usage

1. **Connect your ESP8266 to Wi-Fi:**

   Update the `ssid` and `password` variables in the code with your Wi-Fi network credentials.

   ```cpp
   const char* ssid = "Your_WiFi_SSID";
   const char* password = "Your_WiFi_Password";
