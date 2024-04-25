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

# 2. CONFIGURATION STM32

       ▪ RCC :

![Screenshot from 2024-04-24 15-02-43](https://github.com/TepmarotdanielZ/IMU6050_KalmanFilter_STM32/assets/139426571/3e82bb2b-8a5b-40ef-a3ee-b3809fa4697c)

       ▪ SYS :

![Screenshot from 2024-04-24 15-03-18](https://github.com/TepmarotdanielZ/IMU6050_KalmanFilter_STM32/assets/139426571/39cb064a-408b-47c2-8c98-1c5397652b93)

       ▪ CLOCK :

![Screenshot from 2024-04-24 15-03-36](https://github.com/TepmarotdanielZ/IMU6050_KalmanFilter_STM32/assets/139426571/475caf2f-848d-49fb-b682-f73aafac7c68)

       ▪ I2C :

![Screenshot from 2024-04-24 15-04-04](https://github.com/TepmarotdanielZ/IMU6050_KalmanFilter_STM32/assets/139426571/6a4bb307-b523-4b3a-af9e-440588936f9d)

       ▪ CODE :

![image_2024-04-24_15-04-34](https://github.com/TepmarotdanielZ/IMU6050_KalmanFilter_STM32/assets/139426571/f3fdabcb-d7c7-4336-8096-94088ebb97ce)

![Screenshot from 2024-04-24 15-04-44](https://github.com/TepmarotdanielZ/IMU6050_KalmanFilter_STM32/assets/139426571/a2a552f4-7176-4d39-ad02-7a8765b4be55)


# 3. SCHEMATIC AND CONNECTION

![image](https://github.com/TepmarotdanielZ/IMU6050_KalmanFilter_STM32/assets/139426571/350b4aeb-5e27-4988-a842-1d4eb5367128)

# 4. RESULT TESTING 

# 4. RESULT VDO TESTING 
