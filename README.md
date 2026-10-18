# Autonomous Drone Project

### Vision statement
We envision a student-built autonomous drone that flies campus at night and maps where our buildings lose heat. By bringing together students in geology, engineering, computer science, and sustainability, we aim to turn real data into practical energy insights for Calvin. Along the way we want to create lasting opportunities for interdisciplinary STEM work, where students build something none of them could build alone.

---
### Resources
- <a href="https://mavsdk.mavlink.io">MAVSDK docs</a>.
- <a href="https://github.com/mavlink/MAVSDK-Python">MAVSDK docs Python version</a>. 

---
### Equipment
- **Holybro X650 kit**: the drone itself (frame, motors, battery mount, and a Pixhawk flight controller). It carries everything and flies.
- **Pixhawk flight controller (in the X650 kit)**: the autopilot. It keeps the drone stable and carries out commands such as “fly to this point.”
- **Hadron 640R**: the thermal camera, with a visible camera too. It records a temperature for every pixel, and it sees in the dark, which is needed for night flights.
- **Hadron 640R dev kit**: the adapter for the camera. It connects the camera to the Jetson and includes the drivers to read it.
- **Livox Mid-360**: the LiDAR. It scans the surroundings with lasers to measure distances, so it builds 3D maps and detects obstacles like buildings and trees.
- **Jetson Orin Nano**: the companion computer. It runs the AI model, reads the camera and LiDAR, decides where to fly, and sends commands to the Pixhawk. It also stores the thermal images.

---
### SDK 
**MAVSDK** --> It works with PX4, the autopilot software on the X650.
The alternative is ROS 2 with PX4 offboard mode, documented <a href="docs.px4.io">here</a>. 

### Contacts
- Nathan Harkema:
- _mobile_: 5722994422;
- _email_: nharkema@fibertek.com
