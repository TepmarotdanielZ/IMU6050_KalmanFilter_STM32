# 1. MPU-6050 or IMU SENSOR

MPU6050 sensor module is complete 6-axes Motion Tracking Device. It combines 3-axis Gyroscope, 3-axis Accelerometer and Digital Motion Processor all in small package. Also, it has additional feature of on-chip Temperature sensor. It has I2C bus interface to communicate with the microcontrollers.

![image](https://github.com/TepmarotdanielZ/IMU6050_KalmanFilter_STM32/assets/139426571/cd024bdb-8e32-4bfc-879e-aca1a2164fe8)

      The MPU-6050 module has 8 pins,
      ▪ INT : Interrupt digital output pin
      ▪ AD0 : I2C Slave Address LSB pin. This is 0th in 7-bit slave address of device. If connected to VCC then it is read as logic one and slave address changes.
      ▪ XCL : Auxiliary Serial Clock pin. This pin is used to connect other I2C interface enable sensors ACL pin to MPU-6050.
      ▪ SCL : Serial Clock pin. Connect this pin to microcontrollers SCL pin.
      ▪ SDA : Serial Data pin. Connect this pin to microcontrollers SDA pin.
      ▪ GND : Ground pin. Connect this pin to ground connection.
      ▪ VCC : Power supply pin, connect this pin to +5V DC supply.
