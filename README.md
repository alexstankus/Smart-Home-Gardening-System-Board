**Smart Home Gardening System PCB** 

PCB with light, humidity, and temperature sensing designed for optimizing DIY gardening at home or on a large industrial scale. <br>


**PCB Schematic:** <br><br>
<img width="762" height="539" alt="SoilHealthSchematic" src="https://github.com/user-attachments/assets/a9b5405e-e954-4f27-84f4-96e3fb0245fb" /> <br><br>
**PCB Layout:** <br><br>
<img width="951" height="781" alt="SoilHealthLayout" src="https://github.com/user-attachments/assets/098f6f82-a2ad-4649-adc5-3e276897b2bf" /> <br><br>
**3D View:** <br><br>
<img width="2162" height="1256" alt="SoilHealth3D" src="https://github.com/user-attachments/assets/4ff6dbfc-cb6d-44f0-a2a6-e2b3269e307e" /> <br><br>

This PCB aims to make gardening more accessible and optimized for all people interested. With humidity and temperature sensing, 
this board can be placed in soil to make sure conditions are adequate for growing your specific plant. <br><br>


**Key Features:**

ESP32F4 microcontroller for communication with a database and between sensors <br>

USB-C Power Delivery and Data transfer<br>

Temperature Sensor<br>

Humidity Sensor<br>



**Bill of Materials (BOM)**
<img width="1372" height="671" alt="Screenshot 2025-12-09 at 5 39 36 PM" src="https://github.com/user-attachments/assets/9014efd5-a75c-44e3-9fef-daf7de51ef05" />


**What I Learned** <br><br>
As my first ever PCB project, I learned how to develop a schematic, design a layout, and craft a BOM. The biggest issues I encountered were routing traces efficiently to develop a small board
and finding what connectors to put on my board for my sensors to work. In the datasheets of these sensors there was very little information on how to implement this, but we decided on using 
through holes and saudering the wires (from the sensors) directly to the board. <br>
If I were to do this project again, I would choose different sensors that were more appropriate for my board, and include a PH sensor as that can also dramatically impact plant health. 
<br><br><br>



Alexander Stankus <br>

GitHub: @alexanderstankus <br>
Email: alexstankus99@gmail.com <br><br>


Acknowledgments <br>
Thanks to HOPE (Hands on PCB Engineering) @ UC Berkeley for sponsoring this project and making it possible.
