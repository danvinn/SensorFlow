SensorFlow can **connect** with the remote devices which support **Bluetooth Low Energy.**

My goal was to utilize this terminal and allow **any** compatible microcontroller and sensor to comunicate and transmit data. 

I have utilized Chart.js to preform real-time data representation. 

This can be installed on your homescreen as an application and work offline.

Furthermore, this application establishes **serial communication** over BLE that is not provided by the specification, but needed if you want to make your own BLE IoT devices using affordable bluetooth modules.

  
The application utilises BLE service (`0xFFE0`) and characteristic (`0xFFE1`) available in low cost BLE modules.

 
### Bluetooth Low Energy (Smart) device

  

As mentioned, different BLE devices implement their own services and characteristics to communicate with, but you can build your own simple device: you just need a BLE module (e.g. HM-10, JDY-08, AT-09, CC41-A) and an Arduino Uno. 



 
