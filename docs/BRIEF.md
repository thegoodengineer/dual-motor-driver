# dual motor driver

A dual DC motor driver board a microcontroller can command over a header.

Parts: DRV8833 dual H-bridge, a 12 V barrel jack, a buck converter to 3V3 for logic, bulk electrolytics on the motor rail, and a 2x5 control header.
Power: 12 V in, motor rail direct, logic on 3V3, 1.5 A per channel.
Interfaces: four PWM inputs and one sleep line on the control header, screw terminals for each motor.
Constraints: two layers with a solid ground pour, under 60 by 40 mm, wide traces on the motor rail, and thermal relief on the driver's pad.
