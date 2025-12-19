# 🌙 Automatic Night Lamp Using LDR

This project is a simple **automatic night lamp** that turns ON in darkness and OFF in light using a **Light Dependent Resistor (LDR)**. The circuit is powered by a **12V battery** and uses basic electronic components to demonstrate sensor-based automation.

---

## 📌 Project Overview

The LDR-based night lamp detects ambient light intensity and automatically controls an LED. When the surrounding light level decreases (night), the LED turns ON automatically. When sufficient light is present (day), the LED turns OFF.

This project is ideal for beginners to understand **sensors, transistor switching, and automation circuits**.

---

## 🔧 Components Used

| Component | Quantity |
|---------|----------|
| 12V Battery | 1 |
| LDR (Light Dependent Resistor) | 1 |
| LED | 1 |
| Resistors | 2 |
| NPN Transistor (e.g., BC547) | 1 |
| PCB / Breadboard | 1 |

---

## ⚙️ Working Principle

- The LDR senses light intensity.
- In bright light, LDR resistance is low, keeping the transistor OFF.
- In darkness, LDR resistance increases, activating the transistor.
- The transistor allows current to flow, turning the LED ON.
- The process is fully automatic and requires no manual control.

---

## 🔌 Circuit Description

- The LDR and resistor form a voltage divider connected to the base of the transistor.
- The transistor works as a switch.
- The LED is connected at the collector with a current-limiting resistor.
- A 12V battery supplies power to the entire circuit.

---

## 🎯 Applications

- Automatic night lamps
- Street light automation (basic concept)
- Energy-saving lighting systems
- Sensor-based control projects

---

## 📚 Learning Outcomes

- Understanding LDR working principle
- Basics of transistor switching
- Practical knowledge of automatic control circuits
- Hands-on experience with PCB implementation

---

## 🚀 Future Enhancements

- Use of relay for high-power loads
- Adjustable sensitivity using potentiometer
- Solar-powered battery charging
- Use of microcontroller for smart control

---

## ⭐ Conclusion

This project demonstrates a low-cost and efficient method to automate lighting using basic electronics components. It is simple, reliable, and suitable for academic and beginner-level projects.

