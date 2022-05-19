# ControlTap Console
The ControlTap Console can be used in two different configurations: **Standard** and **Standalone**.

![ControlTap Console](/src/assets/controltapconsole1.jpg | height=300)

### Standard (Wired)
Utilized for most situations that require power or data interuptions. The Standard console interfaces with any ControlTap Module capable of direct (wired) connection.

#### Standalone (Wireless)
For situations where it does not make sense to create a direct connection to the attached equipment:
- Equipment power or control systems are located far away from the Console (usually more than 6 feet) or a power/data cable cannot be routed between the equipment controls and the Console due to physical access restrictions.
- 120V outlet control is required.
- Equipment does not have a suitable control (power or data) interface to tie into.

# ControlTap Module

## HV Module - wired
Operating in standard mode, this NO/NC relay module can be integrated in custom power control systems where high voltage or high current requirements exist.
The user can choose to interface between NO or NC contacts directly at the relay itself.
Module Power Interface:
- Direct connection to NO/NC spade terminals
- Voltage (Max): 240VAC
- Current (Max): 20A NO, 10A NC
Module Control Interface:
- Wired (4 pin) direct connection to ControlTap Console
- Powered by ControlTap Console or wall adapter
- Voltage: 5VDC
- Current: 1.5A

![High Voltage Module](/src/assets/controltaphvmodule1.jpg | height=300)

## 120V Module - wireless
Operating in standalone mode, the 120V Module connects to the CardTap Cloud independently of the ControlTap Console it is paired with.
Module Power Interface:
- Standard 120VAC, 15A Receptacle
- Operating Voltage: 120VAC
- Maximum Current: 8A resistive, 3A inductive
Module Control Interface:
- Wireless (WiFi) standalone connection to CardTap Cloud
- Operating Voltage: 120VAC
- Average "Enabled" Power Consumption (without external load): 4W

![120V Module](/src/assets/controltap120vmodule1.jpg | height=300)

## USB Module - wired
Operating in standard mode, the USB Module (and integrated hub) allows enable/disable control of up to three USB 2.0 ports, usually associated with a keyboard and mouse. The ControlTap Module, Console, and connected USB devices are powered and communicate to the host computer via a single USB cable.
Module Power Interface:
- 1x USB-C port (to computer)
- 3x USB-A ports (to USB devices)
- Voltage: 5VDC
- Current available to downstream USB depends on USB host. *Most USB 2.0 ports will provide a maximum of 300mA to downstream devices after taking into account ControlTap Console and USB Module power requirements*
Module Control Interface:
- Wired (4 pin) direct connection to ControlTap Console
- Powered by USB host

![USB Module](/src/assets/controltapusbmodule1.jpg | height=300)

## Indicator Module - wired
Operating in standard mode, the Indicator Module can display status colors of red, orange, and green for "Standby", "In-use", and "Disabled" ControlTap states. The color-state pairing is user-selectable during setup.
Module Control Interface:
- Wired (4 pin) direct connection to ControlTap Console
- Voltage: 12VDC
- Current: 1A
Other Details:
- 50mm diameter transparent frosted dome (selectable red, orange, and green illumination when powered)
- Mounting via panel mount, wall mount (x2 screws), or magnet mount

![Indicator Light Module](/src/assets/controltapindicatormodule1.jpg | height=300)
