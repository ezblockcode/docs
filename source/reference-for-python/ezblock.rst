Reference for Python
================================

import everything

```python
from ezblock import *
```

Methods
-----------------------------

- :mod:`delay` - Delay for the given number of milliseconds.

```python
delay(ms)
```

- :mod:`print` - replace the original print function to print via bluetooth.

```python
print(msg, end="/n", tag='[DEBUG]')
```

- :mod:`mapping` - masp a value from a range to another

```python
mapping(x, inmin, inmax, outmin, outmax)
```

Classes
------------------------------

.. toctree::
    :maxdepth: 1

    Pin
    ADC
    PWM
    Servo
    UART
    I2C
    Remote
    IOT
    Music
    Color
    Camera
    TTS
    IRQ
    WiFi
    Taskmgr
    SendMail
    Ultrasonic
    DS18X20
    ADXL345
    RGB_LED
    Buzzer
    Sound
    Joystick
    LED
    Switch
    BLE