---
layout: default
title: Micro:bit Incubator Project
---

{% include nav.html %}

# 🔥 Micro:bit Incubator Project

This project involved creating a **cardboard-box incubator** powered by a **BBC Micro:bit**.  
The goal was to **maintain the temperature inside the box within a specific range** and provide **visual feedback** on the Micro:bit’s LED screen.

---

## 🛠 What I Did
- **Built an incubator** out of a cardboard box with insulation to trap heat.  
- Connected the **Micro:bit** to:
  - A small **heating element** to raise the temperature.
  - A **temperature sensor** to monitor the internal environment.
- Programmed the Micro:bit to:
  - **Turn the heater on/off** to keep the incubator within the target range.
  - **Display symbols** on the LED grid:
    - ✅ **symbol** when the temperature was in range.
    - 🔺 **Warning symbol** if it became too hot.
    - ❌ **symbol** if it became too hot for more than 10 seconds.

---

## 💡 How It Worked
- When the temperature sensor detected a drop below the set threshold, the Micro:bit **activated the heater**.  
- When the box overheated, it would **turn the heater off**.  
- The Micro:bit **instantly updated the LED display** to let the user know the status at a glance.

---

## 📈 What I Learned
- How to use the Micro:bit’s **pins** for input (sensor) and output (heater control).
- How to write simple **control logic** in MakeCode/Python to react to sensor readings.
- Basic principles of **feedback loops** (maintaining balance between heating and cooling).

---

## 🚀 Next Steps
- Add **data logging** so temperature changes are recorded over time.
- Use a **more durable enclosure** for better insulation.
- Possibly integrate a **web or phone app** for live monitoring.

