# Wi-Fi Controlled Infinity Mirror (Ultra-Compact Design)

This project demonstrates a **Wi-Fi controlled infinity mirror lighting system** built using the **ESP8266 microcontroller** and **addressable RGB LED strips**.

The mirror creates an **optical illusion of infinite depth** using a two-mirror arrangement while allowing **wireless control of lighting effects through Wi-Fi**.

The main goal of this project was to design a **very compact infinity mirror**, where the **actual optical chamber thickness is only 2 cm**, while still fitting all required electronics and lighting components.

---

# Project Objective

Most infinity mirrors available online typically use **5–10 cm deep frames**.

The goal of this project was to **minimize the thickness while maintaining the infinity effect**.

To achieve this, the entire system was engineered using **thin materials and compact electronics placement**.

---

# Compact Design Breakdown

Although the frame used is a **3 cm shadow box frame**, the **actual internal optical depth is only 2 cm**.

Each component thickness was carefully planned.

### Internal Thickness Distribution

Front panel: **1 mm clear acrylic sheet**

Two-way mirror layer: **1 mm mirror film applied on acrylic**

LED strip thickness: **5 mm**

Electronics cavity depth: **5 mm**

Rear mirror: **2 mm glass mirror**

Back panel: **2 mm**

This allowed the entire system to remain **extremely compact while maintaining strong optical reflections**.

---

# Challenge: Finding a Thin Mirror

One of the biggest challenges during this build was **finding a thin mirror**.

Most local glass vendors only provide mirrors starting from **4 mm thickness**, which would have increased the total system depth.

After visiting several vendors, I eventually found a **small 2 mm mirror from a local mirror shop**, which perfectly matched the design requirement.

Using this mirror allowed the infinity chamber to remain **within the 2 cm design constraint**.

---

# Frame Design

The mirror is mounted inside a **shadow box frame**.

A shadow box frame provides:

- A recessed cavity for electronics and LEDs
- Structural rigidity
- Clean aesthetic design for wall decoration

Although the frame itself is **3 cm thick**, the **functional optical chamber remains only 2 cm**.

---

# Control System

The lighting system is controlled using an **ESP8266 (NodeMCU)** running **WLED firmware**.

Users can control the lighting using:

- WLED mobile application
- Web browser interface
- Wi-Fi network connection

---

# No-Code Implementation

This project intentionally avoids writing custom firmware.

Instead, it uses **WLED**, which provides:

- Pre-built LED animations
- Brightness control
- Color selection
- Wi-Fi configuration
- Real-time lighting effects

Because of this, the project can be controlled **without writing a single line of code**.

---

# Features

- Ultra-compact infinity mirror design
- **Actual optical depth of only 2 cm**
- Wi-Fi controlled RGB lighting
- No custom firmware required (WLED)
- Multiple lighting animations
- Adjustable brightness and color
- Smartphone control
- Clean mechanical assembly

---

# Hardware Components

- ESP8266 (NodeMCU)
- WS2812B Addressable RGB LED Strip
- 2 mm Glass Mirror
- 1 mm Clear Acrylic Sheet
- Two-way mirror film
- Shadow box frame
- 5V power supply
- Back panel board

---

# Working Principle

The infinity mirror effect is achieved using two mirrors.

**Rear Mirror**

A fully reflective mirror placed at the back.

**Front Mirror**

A semi-reflective mirror created using **two-way mirror film applied on acrylic**.

RGB LEDs are placed between these mirrors.

When LEDs turn on, light reflects repeatedly between the mirrors, creating the illusion of an **infinite tunnel of light**.

---

# Applications

- Smart home decorative lighting
- Gaming room lighting
- Interior wall decoration
- Interactive art installations
- IoT lighting projects

---

# Technologies Used

- ESP8266 Wi-Fi Microcontroller
- WLED Firmware
- Addressable RGB LEDs (WS2812B)
- IoT wireless lighting
- Optical reflection system

---

# Future Improvements

- Custom PCB for compact electronics
- Audio reactive lighting
- Smart home integration
- Larger infinity mirror panels

---

⭐ If you found this project interesting, feel free to **star the repository**.
