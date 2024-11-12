# Design a Power Supply Circuit with a 5V Regulator and Dual LED Indicators

### Objective
Design and simulate a DC power supply circuit that takes in an unregulated DC input (9V) and outputs a regulated 5V using a 7805 voltage regulator, including LED indicators for both input and output power. Design a PCB for the above.

### Components Required
1. Voltage Regulator: 7805 (5V regulator)
2. Diode: 1N4007 (for reverse polarity protection)
3. Capacitors:
   - 100nF ceramic capacitor (input and output filtering)
   - 10μF electrolytic capacitor (input and output smoothing)
4. LEDs:
   - 5mm Red LED (for 9V input power indication)
   - 5mm Green LED (for 5V output indication)
5. Resistors:
   - Resistor for Red LED (to be calculated)
   - Resistor for Green LED (to be calculated)
6. Power Source: 9V battery or 9V DC input
7. Terminal Blocks: 2-pin terminal blocks for input and output connections

### PCB Design Tools
- Altium (educational license)
- KiCad (open-source)
- EasyEDA (web-based, beginner-friendly)

### Design Requirements
1. **Verify Design Rules (DRC)**
   - Run a Design Rule Check
   - Ensure no unconnected traces or short circuits

2. **Export Gerber Files**
   - Export files for PCB manufacturing

### Key Learning Outcomes
1. Understand the role of voltage regulators, diodes, capacitors, resistors, and LEDs
2. Learn how to calculate resistor values for LEDs
3. Develop proficiency in PCB layout
4. Gain practical experience with schematic design
5. Learn how to prepare a PCB for manufacturing

### Resources
- [PCB Design](https://www.protoexpress.com/kb/pcb-design-resources/)
- [KiCAD Playlist](https://youtube.com/playlist?list=PL3bNyZYHcRSUhUXUt51W6nKvxx2ORvUQB&si=EC7669NwmyZqB4qV)