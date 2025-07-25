# Handheld-taser-

⚡ Handheld Taser (400,000V) – DIY Project
A compact, rechargeable handheld taser powered by a 18650 lithium battery. Designed for personal safety and learning, this project integrates a high-voltage boost converter, a TP4056 charging module, LED indicator, and dual-switch activation for safety.

🔧 Components Used
Component	Description
400,000V Boost Module	High-voltage pulse generator
18650 Li-ion Battery	Rechargeable battery (3.7V ~ 4.2V)
TP4056 Charging Module	USB-based battery charging and protection
Main Switch	Toggles power to the taser module
Pushbutton	Momentary activation of taser
LED Indicator	Displays power/charging status
Resistors, Wires, Heat Shrink, Case	For connections and safety

⚙️ Circuit Overview
text
Copy
Edit
+------------------------+
|  18650 Battery (3.7V)  |
+------------------------+
            |
        [TP4056]
        |      |
    Output     USB input (for charging)
        |
    [Main Switch]
        |
       +-------> LED Indicator (with current limiting resistor)
        |
    [Pushbutton]
        |
    [400,000V Boost Module]
        |
     Output (Electrodes)
The main switch ensures accidental activation is prevented, while the pushbutton controls the high-voltage output only when deliberately pressed.

🚨 Safety Notes
⚠️ Extremely high voltage – not a toy.

⚠️ Never touch the output wires or terminals while powered.

✅ Keep away from children.

✅ Use only for educational or emergency self-defense purposes.

⚠️ Always test in controlled environments with insulated tools.

📸 Images
(Add real images or Fritzing diagrams here)
If you want, I can also help generate a clean wiring diagram or 3D-printable case.

🔋 Charging the Device
Plug a 5V USB cable into the TP4056 module.

The LED on TP4056 will indicate:

Red = Charging

Blue/Green = Fully Charged

🧠 Project Goals
Practice working with high-voltage modules

Build a real-world battery-powered circuit

Design safe activation logic (main + momentary switch)

🛡 Disclaimer
This device is built for educational and prototyping purposes only. The creator is not liable for any misuse, harm, or legal implications. Always check local laws and regulations before using or carrying stun devices.

💡 Future Improvements
Add battery voltage display (using a small OLED or voltage divider)

Lock/unlock system with a keypad or RFID

Over-voltage protection for safer charging

3D-printed enclosure with safety vents
