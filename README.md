# HTPC playbook
This is an ansible playbook for configuring my HTPC.

# Hardware
Nvidia GTX 980

## What is installed
- Nvidia Drivers (from graphics-drivers ppa)
- Kodi
- Steam

## Configuration
- Allow wakeup via IR remote control (needs to be made generic)
- Setup remote keys via ir-keytable (Current only the keymap file is added, need to determine how to configure via ansible)

## More to do
- https://github.com/atar-axis/xpadneo
- Launch Steam in Big Picture Mode from Kodi
- Emulators?