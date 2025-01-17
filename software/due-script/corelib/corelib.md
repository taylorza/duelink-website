# Core Library

---

The core library gives DUE Scripts the necessary API to access hardware. It has other software related libraries as well. These API functions are available from within DUE Scripts and runs host-less. When using a host, a library for that particular library is provided to reflect the DUE Core library. For example, when using Python, the provided Python library includes `dev.Led.Set(200,800,20)` which mirrors the [LED](led.md) API.

| API       | Use          |
| :--- |:---|
| [Analog](analog.md) | Read or Write analog pins |
| [Button](button.md) | Read a button. Similar to Digital read but handles debounce |
| [Demo](demo.md) | Built-in demos |
| [Digital](digital.md) | Read or write digital pins |
| [Distance](distance.md) | Read ultrasonic distance sensor |
| [Frequency](frequency.md) | Generate frequency on a specific pin. This uses hardware PWM internally|
| [I2C](i2c.md) | Access the I2C bus for transferring data |
| [Infrared](infrared.md) | Read and decode IR remote control signal |
| [LCD](lcd.md) | Draw on LCD (device specific) |
| [LED](led.md) | Control the onboard LED |
| [NeoPixel](neopixel.md) | Control smart color LEDs |
| [Servo](servo.md) | Control servo motors |
| [Sound](sound.md) | Generate sounds on the device's speaker (device specific) |
| [SPI](spi.md) | Access the SPI data bus |
| [Touch](touch.md) | Allows for capacitive touch sensing |
| [UART](uart.md) | Transfer data on the UART serial port |

