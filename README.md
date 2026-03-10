<div align="center">
  
  <h1>Hi there, I'm Abdelfattah Ahmed 👋</h1>
  <h3>Aeronautical Engineer | UAV Autonomy | Robotics</h3>

  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=24&duration=3000&pause=1000&color=F97316&center=true&vCenter=true&width=800&lines=Aerospace+%26+Aeronautical+Engineer;CFD+%26+FEA+Specialist;Autonomous+UAV+Developer;Robotics+%26+Flight+Control" alt="Typing SVG" /> 

  <br><br>

  <a href="https://www.linkedin.com/in/abdelfattah-ahmed7/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:aapdo669@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
</div>

<br>

<table align="center" style="border-collapse: collapse; border: none;">
  <tr style="border: none;">
    <td width="60%" valign="top" style="border: none;">
      <h2>🚀 About Me</h2>
      <ul>
        <li>🎓 <b>Senior Aeronautical & Aerospace Engineering Student</b> at New Mansoura University.</li>
        <li>🤖 Deeply passionate about <b>Autonomous UAVs, Robotics, and Computer Vision</b>.</li>
        <li>🛩️ Completed over <b>+50 projects</b>, specializing in <b>CFD and FEA analyses</b> to optimize aerodynamic performance.</li>
        <li>🧠 Skilled in <b>Flight Control, Sensor Fusion (LiDAR/IMU), and Autonomous Navigation</b>.</li>
      </ul>
      
      <h3>🔬 Research Interests</h3>
      <p>
        🛸 <b>Autonomous UAV Navigation</b> | 🗺️ <b>SLAM for Aerial Robotics</b> <br>
        🕹️ <b>Flight Control Systems</b> | 🌪️ <b>Aerodynamic Optimization</b>
      </p>
    </td>
    <td width="40%" align="center" style="border: none;">
      <img src="https://media.giphy.com/media/26tn33aiTi1jIGsnu/giphy.gif" width="100%" alt="Gazebo Simulation GIF" style="border-radius: 12px; box-shadow: 0 4px 8px rgba(0,0,0,0.2);"/>
      <br>
      <i><small>ROS/Gazebo Autonomous Navigation & SLAM</small></i>
    </td>
  </tr>
</table>

---

## 💼 Experience & Training

- **Egyptian Space Agency (EgSA)** | *Space Keys Trainee* 🛰️
  - Hands-on training on critical satellite subsystems (EPS, OBC, Communications, ADCS, Payload, and Structures).
- **EgyptAir Training Academy** | *Airframe & Power Plant Trainee* ✈️
  - Gained practical experience with aircraft systems, maintenance processes, safety protocols, and aeronautical diagnostics.

---

## 🏆 Honors & Certifications

- 🥉 **3rd Place, Smart Cities Hackathon:** Developed a *Cosmic Ray Energy Harvesting Satellite Project* for renewable energy transmission.
- 🎓 **Autonomous Mobile Robot ROS Diploma (Parts I & II):** Mastered ROS, Gazebo, SLAM, Kinematics, and EKF sensor fusion.
- 🚁 **Pixhawk Quadcopter Mastery:** Proficient in assembly, Mission Planner configuration, and autonomous mission planning.
- ⚙️ **ANSYS Simulation & FEA Training:** Advanced structural analysis, meshing, and finite element modeling.

---

## 🧠 Current Flagship Project

### 🛸 Autonomous UAV Platform: Threat Detection, 3D Mapping & Navigation
Developing a fully autonomous UAV system focusing on robust navigation and situational awareness through multisensor fusion.

- **Capabilities:** Fully autonomous navigation, Real-time 3D mapping, and onboard threat detection.
- **Algorithms:** Sensor fusion combining multiple sources (LiDAR, Camera, IMU) for accurate SLAM.

#### ⚙️ System Architecture (ROS-PX4 Integration)
```mermaid
graph LR
    A[Sensors <br> Camera / LiDAR] -->|Raw Data| B(Computer Vision <br> & SLAM)
    B -->|Odometry / Map| C{ROS Navigation Node}
    C -->|Velocity Commands| D[MAVROS]
    D -->|Offboard Control| E((PX4 Autopilot))
    E -->|PWM Signals| F[Actuators / Motors]
    
    style A fill:#22314E,color:#fff,stroke:#333,stroke-width:2px
    style C fill:#021F36,color:#fff,stroke:#333,stroke-width:2px
    style E fill:#F97316,color:#fff,stroke:#333,stroke-width:2px
