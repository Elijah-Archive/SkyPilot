# SkyPilot (Archive)

**Originally built:** ~2022 • **Status:** Archived • **Stack:** Python (djitellopy, Pygame, OpenCV)

## What it does
**SkyPilot** is a keyboard-driven control system for the DJI Tello drone.  
It lets you fly, maneuver, and visualize drone position using simple keystrokes.  

All that’s required is a **DJI Tello drone** and Python installed on your machine.  
This project was built to make drone piloting accessible through **keyboard input**  
and provide **visual feedback** of movement in a Pygame/OpenCV window.  
Controls

Arrow keys – move left/right/forward/backward

W/S – up / down

A/D – rotate left / right

E – takeoff

Q – land

P – exit program

File overview

keypressmodule.py – custom Pygame keyboard input handler.

testaero.py – main drone control loop + visualization.

tst.sql – sample SQL experiments (unrelated to drone logic).
## Quickstart
```bash
# prerequisites
Python 3.10+
pip install djitellopy pygame opencv-python numpy

# run
python test32224.py

