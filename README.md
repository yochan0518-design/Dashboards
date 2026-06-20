What this code does:
The Grid Layout: Uses CSS flexbox and grid to arrange a neat control panel next to the joystick.
The Joystick: Listens for touchstart and touchmove events. It uses a bit of math (trigonometry!) to ensure the glowing stick never drags outside the boundary of the dark circle.
The Readout (Telemetry): Automatically translates the physical pixels you drag into a -100% to 100% scale, which is exactly how real game controllers send data to the computer for Pitch and Roll.
The Buttons: Feature a satisfying "press down" CSS animation and toggle a red "engaged" state when tapped.
