# EEBalanceBug - Self-balancing autonomous maze-mapping rover (2nd Year Summer Project)
The primary objective of this project is to construct a prototype self-balancing rover capable of autonomously traversing a maze, mapping its layout, and finding the shortest path from the start to the endpoint. 
![image](https://github.com/bhavyaEE/EEBalanceBug/assets/107200668/028ead33-4e99-4d04-a98c-3836abf7195a)

The  navigation  of  the  maze  was conducted  using  computer  vision  with  a  D8M  camera  module,  and  ultrasonic  sensors  to  detect  and measure the placement of white LED strips which signify maze walls. Further to this, determining the rover’s  position  within  the  maze  and  in  relation  to  the  white  LED  strips,  was  achieved  using  the MPU6050  inertial  measurement  unit,  capable  of  finding  the  Euler  angles  and  using  methods  of triangulation with beacons, and deadreckoning to determine displacement. The term ‘beacon’refers to three self-powered LEDs supplied by energy from solar panels. Whilst moving and balancing on two wheels, the rover sends the coordinates of the path it has traversed and the surrounding maze walls in real-time to the server to build up the map of the maze and ultimately find the shortest path. 
![image](https://github.com/bhavyaEE/EEBalanceBug/assets/107200668/77f6e57c-6d92-4c2c-a01a-b0a43258bde8)

![image](https://github.com/bhavyaEE/EEBalanceBug/assets/107200668/c938b501-4d04-4d6c-8156-e4b0bf833ca0)

![image](https://github.com/bhavyaEE/EEBalanceBug/assets/107200668/94d074aa-630f-4c5e-bc11-890eed5533ff)


![image](https://github.com/bhavyaEE/EEBalanceBug/assets/107200668/34c6b758-2db2-46d7-8fcf-388eacd69d9e)


![image](https://github.com/bhavyaEE/EEBalanceBug/assets/107200668/c335ed91-30b1-4b86-a2d6-66b5bbf26a22)
![image](https://github.com/bhavyaEE/EEBalanceBug/assets/107200668/7f782a8c-093e-476f-915d-72aaf162bd38)


