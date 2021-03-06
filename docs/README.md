
# ControlTap Console

<img src="https://github.com/CardTap-Systems-LLC/wiki/raw/main/docs/assets/controltapconsole1.png" height="300">

The ControlTap Console can be used in two different configurations: **Standard** and **Standalone**.

### Standard (Wired)
Utilized for most situations that require power or data interuptions. The ControlTap console can directly interface with any ControlTap Module capable of direct (wired) connection.

### Standalone (Wireless)
For situations where it does not make sense to create a direct connection to the attached equipment:
- Equipment power or control systems are located far away from the end-user and ControlTap Console (usually more than 6 feet) or a power/data cable cannot be routed between the equipment controls and the Console due to physical access restrictions.
- 120V wall outlet control is required.
- Equipment does not have a suitable control (power or data) interface to tie into.

<br/>

# ControlTap Module

## HV Module -  Standard (Wired)

<img src="https://github.com/CardTap-Systems-LLC/wiki/raw/main/docs/assets/controltaphvmodule1.png" height="300">

This NO/NC relay module can be integrated in custom power control systems where high voltage or high current requirements exist.
The user can choose to interface between NO or NC contacts directly on the relay itself.
Module Power Interface:
- Direct connection to NO/NC spade terminals
- Voltage (Max): 240VAC
- Current (Max): 20A NO, 10A NC
Module Control Interface:
- Wired (4 pin) direct connection to ControlTap Console
- Powered by ControlTap Console or wall adapter
- Voltage: 5VDC
- Current: 1.5A

## 120V Module - Standalone (Wireless)

<img src="https://github.com/CardTap-Systems-LLC/wiki/raw/main/docs/assets/controltap120vmodule1.png" height="300">

Operating in standalone mode, the 120V Module connects to the CardTap Cloud independently of the ControlTap Console it is paired with.
Module Power Interface:
- Standard 120VAC, 15A Receptacle
- Operating Voltage: 120VAC
- Maximum Current: 8A resistive, 3A inductive
Module Control Interface:
- Wireless (WiFi) standalone connection to CardTap Cloud
- Operating Voltage: 120VAC
- Average "Enabled" Power Consumption (without external load): 2W

## USB Module - Standard (Wired)

<img src="https://github.com/CardTap-Systems-LLC/wiki/raw/main/docs/assets/controltapusbmodule1.png" height="300">
<img src="https://github.com/CardTap-Systems-LLC/wiki/raw/main/docs/assets/controltapusbmodule2.png" height="300">

The USB Module (and integrated hub) allow enable/disable control of up to three USB 2.0 ports, usually associated with a keyboard and mouse. The ControlTap Module, Console, and connected USB devices are powered and communicate to the host computer via a single USB cable.
Module Power Interface:
- 1x USB-C port (to computer)
- 3x USB-A ports (to USB devices)
- Voltage: 5VDC
- Current available to downstream USB depends on USB host. *Most USB 2.0 ports will provide a maximum of 300mA to downstream devices after taking into account ControlTap Console and USB Module power requirements*
Module Control Interface:
- Wired (4 pin) direct connection to ControlTap Console
- Powered by USB host

## Monitoring/Light Indicator Module - Standard (Wired) _(preliminary prototype specs only)_

<img src="https://github.com/CardTap-Systems-LLC/wiki/raw/main/docs/assets/controltapindicator1.png" height="300">

The Indicator Module can display status colors of red, orange, and green for "Standby", "In-use", and "Disabled" ControlTap states. The color-state pairing is user-selectable during setup.
Indicator Module can also interface with various digital and analog inputs as "alarm" triggers if equipment is enabled without proper authorization.
Module Control Interface:
- Wired (4 pin) direct connection to ControlTap Console
- Voltage: 12VDC
- Current: 1A
Other Details:
- 50mm diameter transparent frosted dome (selectable red, orange, and green illumination when powered)
- Considering mounting via panel mount, wall mount (x2 screws), or magnet mount

Module Input Options:
- Isolated digital input: 3-30VDC
- Analog input: 0-12VDC
- AC Current Clamp-on meter: 0-30A AC
On-Board Selectable Options:
- Analog/AC alarm threshold: Trim pot
- Analog/digital input: DIP switch
- Alarm lighting solid/flash: DIP switch
- Alarm buzzer enable: DIP switch
- Indicator only/Monitoring mode: DIP switch
