First version of a PCB designe for a flight controller for model aircrafts and drones. 
The system has been developed around the Arduino Nano microcontroller board. The developer can develop 
and implement different control algorithms for flight control on this board. The PCB has been designed 
to accomodate the following:
1) Arduino Nano
2) GY-87 (or GY-86) sensor (Consists of MPU6050 (3-axis Gyro + 3-axis Acceleration), 
   HMC5883L (3-axis Magnetic Field), BMP180 (Air Pressure Sensor)
3) MP-1584 mini buck converter

There are extension pads for the following:
1) 6 PWM outputs
2) PWM pin D3 can be used as ext interrupt pin
3) GPS module (pins D7 & D8)
4) Hardware serial for serial transceiver
5) Extra I2C slot
6) Analog i/o pin A0

2 x 1206 size 4.7K ohm resistor have to be added as pull up resistors on the I2C lines.