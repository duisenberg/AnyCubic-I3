<h3>Marlin 1.1.5 for Anycubic I3</h3>

The config files contain a setup for the Anycubic I3, use with care.

Features:
- Trigorilla board
- both Z-steppers on one driver 
- Bed probe using Z endstop
- Autolevel bilinear enabled
- reversed encoder logic
- 250k serial speed
- 256 Byte TX buffer
- 290 deg C nozzle limit
- bed size 210x210

The encoder steps are set quite high to make babystepping and Z-offset setting a bit less tricky. The temp limit for nozzle is 
increased to avoid a hard reset when it overshoots the target temp for about 10-15 deg at first heatup. 

