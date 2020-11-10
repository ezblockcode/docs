Reference for Python
====================

ezblock
--------
Under ezblock, the classes and methods used

import everything
:code:`from ezblock import *`


Methods
^^^^^^^


- :mod:`delay` - Delay for the given number of milliseconds.

:code:`delay(ms)`

- :mod:`print` - replace the original print function to print via bluetooth.

:code:`print(msg, end="/n", tag='[DEBUG]')`

- :mod:`mapping` - masp a value from a range to another

:code:`mapping(x, inmin, inmax, outmin, outmax)`

Classes
^^^^^^^

.. toctree::
    :maxdepth: 1

    ezblock/Pin
    ezblock/ADC
    ezblock/PWM
    ezblock/Servo
    ezblock/UART
    ezblock/I2C
    ezblock/Remote
    ezblock/IOT
    ezblock/Music
    ezblock/Color
    ezblock/Camera
    ezblock/TTS
    ezblock/IRQ
    ezblock/WiFi
    ezblock/Taskmgr
    ezblock/SendMail
    ezblock/Ultrasonic
    ezblock/DS18X20
    ezblock/ADXL345
    ezblock/RGB_LED
    ezblock/Buzzer
    ezblock/Sound
    ezblock/Joystick
    ezblock/BLE

PiMobile
--------
Methods
^^^^^^^
Classes
^^^^^^^
.. toctree::
    :maxdepth: 1

    pimobile/robothat