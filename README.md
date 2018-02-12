[![ MMA8452Q](MMA8452Q_I2C.png)](https://store.ncd.io/product/mma8452q-3-axis-12-bit8-bit-digital-accelerometer-i2c-mini-module/).

#  MMA8452Q

Manufactured by Freescale Semiconductor, Inc., the MMA8452Q is a smart, low-power, three-axis, capacitive, micro-machined accelerometer with 12 bits of resolution.
This Device is available from www.ncd.io 

[SKU: MMA8452Q]

(https://store.ncd.io/product/mma8452q-3-axis-12-bit8-bit-digital-accelerometer-i2c-mini-module/)
This Sample code can be used with Raspberry Pi.

Hardware needed to interface MMA8452Q 3Axis accelometer sensor With Raspberry Pi :
1. <a href="https://store.ncd.io/product/mma8452q-3-axis-12-bit8-bit-digital-accelerometer-i2c-mini-module/">MMA8452Q 3Axis accelometer sensor</a>
2.  <a href="https://store.ncd.io/product/i2c-shield-for-raspberry-pi-3-pi2-with-outward-facing-i2c-port-terminates-over-hdmi-port/">Raspberry Pi I2C Shield</a>
3. <a href="https://store.ncd.io/product/i%C2%B2c-cable/">I2C Cable</a>

## Python
Download and install smbus library on Raspberry pi. Steps to install smbus are provided at:

https://pypi.python.org/pypi/smbus-cffi/0.5.1

Download (or git pull) the code in pi. Run the program.

```cpp
$> python MMA8452Q.py
```
The lib is a sample library, you will need to calibrate the sensor according to your application requirement.
