# Wi-Fi Controlled Infinity Mirror (3 cm)

This project demonstrates a **Wi-Fi controlled infinity mirror lighting system** built using the **ESP8266 microcontroller and RGB LED strips**.  
The mirror creates an **optical illusion of infinite depth** using a two-mirror arrangement while allowing wireless control of lighting effects through Wi-Fi.

The entire system is designed in a **compact 3 cm thick frame**, making it suitable for decorative and smart-lighting applications.

---

## Features

- Ultra-thin **3 cm infinity mirror design**
- **Wi-Fi based lighting control**
- Multiple RGB lighting effects and animations
- Adjustable brightness and colors
- Real-time wireless LED control
- Easy configuration using a smartphone

---

## Control System

The LEDs are controlled using the **Wled mobile application**, which runs on the ESP8266.

**Important:**  
This project uses **WLED firmware**, therefore **no custom Arduino code was written**.  
All LED effects, brightness control, and color patterns are managed directly through the WLED interface.

---

## Hardware Components

- ESP8266 (NodeMCU)
- WS2812B Addressable RGB LED Strip
- One-way mirror (acrylic mirror film)
- Standard reflective mirror
- Power supply
- Wooden / acrylic frame (3 cm thickness)

---

## Working Principle

The infinity mirror effect is achieved by placing:

1. A **fully reflective mirror at the back**
2. A **semi-transparent one-way mirror at the front**

RGB LEDs are placed between the two mirrors. When the LEDs turn on, light reflects repeatedly between the mirrors, creating the illusion of **infinite depth**.

The ESP8266 runs WLED firmware and connects to Wi-Fi.  
Users can control LED animations, brightness, and colors through the **WLED mobile app or web interface**.

---

## Applications

- Smart home decorative lighting
- Gaming room lighting
- Interior wall decoration
- Interactive art installations
- IoT lighting projects

---

## Technologies Used

- ESP8266 Wi-Fi Microcontroller
- WLED Firmware
- Addressable RGB LED Control
- IoT Wireless Lighting

---

## Project Structure
