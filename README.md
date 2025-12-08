# Simon Vo Engineer Portfolio

  Welcome! I am a student at the University of Southern California studying Aerospace Engineering. Currently I am a aerodynamic member on the USC FSAE team. This is my portfolio.

## Projects

### Wake Deflector (USC FSAE IC)
- **Role:** design + firmware
- **Software:** Siemens NX, Star-CCM+
- **Goals:** Increase downforce and lower yaw sensitivy by creating a aerodynamic component position on the front suspention geometry
- **Skills Learn:** Design for Manufractuing, Aerodynamics Validation using Pitots Tubes, Rapid Iteration, Aerodynamic design & CFD analysis  
- **Result:** Increase downforce in Yaw by 60N, and lower yaw sensitivity by 7%.
- **Repo:** https://github.com/immmmsimon-debug/FSAE-Wake-Deflector
<p align="center">
<img width="250" height="215" alt="image (2)" src="https://github.com/user-attachments/assets/ed54389f-01ff-4d11-9454-89a731703491" />
<img width="133" height="370" alt="image (3)" src="https://github.com/user-attachments/assets/f317cca4-b38d-4ffd-bb6d-358ba5b71f00" />
<img width="117" height="360" alt="image (4)" src="https://github.com/user-attachments/assets/bf6515d6-38c0-4582-80cb-38e93e425d0f" />
<img width="175" height="210" alt="image (5)" src="https://github.com/user-attachments/assets/3dbc07fe-219d-4074-b5c5-6190a69e850a" />
</p>

### Open Steel Frame (USC FSAE IC)
- **Role:** design + simulation
- **Goals:** To create a structural simulation model that will characterize the stiffness of the frame to perform rapid iteration in order to save weight while maitaining desire stifness.
- **Skills Learn:** Structural FEA, Design for Manufractuing, Tube-frame modeling, Simulation correlation & validation against physical measurements, 
- **Result:** Simulated & validated 4130 steel tube chassis (66 lb); reached 2700 Nm/deg frame stiffness @ wheel with 2% simulation error.
<p align="center">
<img width="1614" height="886" alt="Screenshot 2025-12-08 at 8 49 19 AM" src="https://github.com/user-attachments/assets/e5ab6ddb-17c2-4431-807d-f1dafcdcbc7e" />
</p>

### Aero Components Mounts (USC FSAE)
- **Role:** design + firmware + simulation
- **Goals:** Previous aero mount are over engineer, thus the mount need to be redesign to reduce weight in addtion to the increase in the aero package weight.
- **Skills Learn:** Design for Manufracturing, Structural FEA
- **Result:** Reduce Mass by 30% while experiecing 50% more load.
- **Repo:** https://github.com/immmmsimon-debug/FSAE_Aerodynamic_Mount
<p align="center">
<img width="1313" height="509" alt="image" src="https://github.com/user-attachments/assets/bfcbb548-97d9-4568-a8d3-6666388ed6f3" />

</p>

### Orbes Sensor Fusion and Motor Control (Orbital Entertainment System)
- **Stack:** Python, C++, ESP32, Raspberry pi 5, Adafruits 9DOF IMU, Infrared Cameras, PiCam
- **Result:** Implemented AprilTag yaw detection with 0.1° accuracy within 2 m for real‑time orientation control. Achieved 6 s settle time for 90° start–stop maneuvers.
- You can see all reasoning, and final result inside the PowerPoint presentation where I partake in: The overal avionic/software artitechutre, communication protocal, Bus system, Camera Tracking system, Loggin, and sensors.
  - To summarize:
    - I created a sensor fusion code using the IMU gyro and accel data to eliminate drift in roll and pitch.
    - In order to control the yaw drift, a april tag system was made, this also allow us to detect how far we are from the ground
    - Created a bus system that guarantee fresh data is being fed into the Kalman Filter.
    - Created a bus system that fed LQR output from the Pi into the ESP32s
    - Help create the infared tracking program, but creating a PID that takes in the difference in pixel and output the require torque into the ESPs
    
- **Flaw:** The orbe still experience gimble lock, due the fact that we are still using Eular angles instead of Quadternions. Due to the fact that we are using IR we do not hae depth perception thus the tracking might over estimate how much it have to move. 





## About
Currently a 2nd Year in Aerospace Engineering. Interested in Design, Analysis, and Controls.

## Contact
smvo@usc.edu, vvxuankhang@gmail.com, 626-804-0853

  
