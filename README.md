# ForgeController
Project to collect ideas, mockups and code to create an open hardware / open software gamepad / game controller

# Ideas / Inspiration

- [Embedded.FM - 304: ADC Channel Six (podcast between OpenSteamController and former Valve Engineer)](https://www.youtube.com/watch?v=q1jXlFICQzs)
- [OpenSteamController](https://github.com/greggersaurus/OpenSteamController)
- projectSpigot - [Hackaday](https://hackaday.io/project/177789/) / [GitHub](https://github.com/ryanayoung/projectSpigot)

# Initial Brainstorming

## Hardware

- Architecture - RISC-V?
- For overall controller shell / design, use Steam Controller CAD files
- Potential interchangeable components = connection, input modules
  - Connection options - USB, Bluetooth, ?WiFi Direct or USB dongle? &rarr; use Framework module standard?
  - Input modules - 2 large / 2 small input modules
    - Large input modules = trackpad, trackpad + 4-way directional button, directional buttons
    - Small input modules = joystick, cross 4-button panel
- Power - USB direct power, AA batteries, ?Li-Ion? module
- Input
  - ?interchangeable (see above) vs same as Steam Controller
  - Quad buttons
  - Trackpad - 4-way vs plain
  - Joystick
  - 4-way buttons
  - Shoulder buttons same as Steam Controller = 1 analog, 1 digital on each side
  - Back handgrip triggers 
  - Menu Button + Start / Select Buttons
  - Gyroscope
  - Accelerometer
  - ?IR sensor (e.g. WiiMote)?

## Software

- Rust vs Python vs C++
- Configurator / remapper
- "Desktop companion app"
