dynamixel_motor
===============
Updated and modified by Hoang Nguyen

ROS stack for interfacing with Robotis Dynamixel line of servo motors using Protocol 2.0. The new 16-bit CRC checksum was brought over from the pyxl320 package by Kevin Walchko https://github.com/MomsFriendlyRobotCompany/pyxl320.

Packet for Protocol 1.0 can be viewed here http://support.robotis.com/en/product/actuator/dynamixel/communication/dxl_packet.htm

Packet for Protocol 2.0 can be viewed here http://support.robotis.com/en/product/actuator/dynamixel_pro/communication/instruction_status_packet.htm

Please setup/update your Dynamixel Motors properly before using this package: (firmware setup/update can be done using R+ Manager 2.0 http://support.robotis.com/en/software/roboplus2/r+manager2/roboplus_manager2.htm):
      
      - Baud rate: should be 1Mbps (different settings can be used, just modified the launch file)
      - Protocol 2.0
      - Flash the latest firmware onto the servo
