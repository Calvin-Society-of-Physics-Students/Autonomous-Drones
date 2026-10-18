# Autonomous Drone Project

#### Vision statement

Attaching a LiDAR module to a drone to study reflectivity as a function of surface material, angle of incidence, and distance — a hands-on way to explore laser optics and time-of-flight ranging.



#### Resources

---

#### Equipment
---

- Holybro X650 kit: the drone itself (frame, motors, battery mount, and a Pixhawk flight controller). It carries everything and flies.
- Pixhawk flight controller (in the X650 kit): the autopilot. It keeps the drone stable and carries out commands such as “fly to this point.”
- Hadron 640R: the thermal camera, with a visible camera too. It records a temperature for every pixel, and it sees in the dark, which is needed for night flights.
- Hadron 640R dev kit: the adapter for the camera. It connects the camera to the Jetson and includes the drivers to read it.
- Livox Mid-360: the LiDAR. It scans the surroundings with lasers to measure distances, so it builds 3D maps and detects obstacles like buildings and trees.
- Jetson Orin Nano: the companion computer. It runs the AI model, reads the camera and LiDAR, decides where to fly, and sends commands to the Pixhawk. It also stores the thermal images.


#### SDK 
---

#### Contacts
- Nathan Harkema: _mobile_: 5722994422; _email_: nharkema@fibertek.com
