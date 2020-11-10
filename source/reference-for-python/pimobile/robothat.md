# robothat Module - Robot Control Boards

Usage:
```python
from robothat import *

motor_direction_calibration(1, 1)          # Calibrate motor direction of rotation

set_motor_speed(1, 50)                     # Set the speed of the motor

motor_speed_calibration(10)                 # Speed calibration of motors              

```
## Constructors
```Robothat Module```
robothat Module allows you to control the robothat board.

## Methods
- motor_direction_calibration - Calibrate motor direction of rotation.(motor: 1 or 2,value: 0 or 1))
```python
motor_direction_calibration(1,0)
```

- set_motor_speed - Set the speed of the motor.(motor: 1 or 2,value:0 ~ 100)
```python
set_motor_speed(1,50)
```

- motor_speed_calibration - #Speed calibration of motors.(value: -100 ~ 100,If the value is greater than zero,the speed of motor 1 will increase the value.
```python
motor_speed_calibration(10)  
```


