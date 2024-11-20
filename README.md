# **Drone Lab Repository**

Welcome to the **Drone Lab Repository**, a collection of projects showcasing various drone programming techniques and flight control experiments using the Tello drone. Each lab explores unique aspects of drone automation and real-time control, blending hardware interaction with software logic to create dynamic and engaging demonstrations.

---

## **Overview**

This repository contains multiple drone missions, ranging from basic flight paths to advanced automation and user-interactive controls. You'll find projects focused on:

- Establishing connections with the drone and configuring command modes.
- Automating navigation for photography and exploration.
- Developing graphical or keyboard-based interfaces for real-time control.
- Utilizing advanced drone capabilities like flips, rotations, and mission pad detection.

---

## **Project Highlights**

### **Lab 4 - Flying in an Equilateral Triangle**  
- **Goal**: Program the drone to fly in a precise equilateral triangle pattern.  
- **Key Features**:
  - Takeoff and altitude adjustments.
  - Forward movement and calculated angular rotations to complete the triangle.
  - Safe landing after completing the flight.

### **Lab 5 - Automated Navigation and Real-Time Control**
#### **Mission 1: Automated Aerial Photography and Navigation**  
- **Goal**: Automate a flight path to capture images at specific locations.  
- **Key Features**:
  - Stream and record live video during the flight.
  - Capture high-resolution images at predefined points.
  - Execute a structured navigation sequence with precise movements and rotations.

#### **Mission 2: Real-Time Drone Control with Keyboard Input**  
- **Goal**: Enable manual control of the drone through keyboard inputs.  
- **Key Features**:
  - Control the drone's movement in all directions (up, down, forward, backward, left, right).
  - Execute advanced maneuvers like flips and rotations using specific keys.
  - Stream and record live video for real-time interaction.

### **Lab 6 - GUI-Based Drone Control**  
- **Goal**: Design a graphical user interface (GUI) for simplified drone control.  
- **Key Features**:
  - A 4x4 grid of buttons for various drone commands (takeoff, flips, altitude changes, etc.).
  - Display telemetry data, such as battery status, height, and temperature.
  - Provide an intuitive interface for beginners and experienced users alike.

### **Lab 7 - Mission Pad Detection**  
- **Goal**: Automate drone navigation to detect and interact with mission pads.  
- **Key Features**:
  - Enable mission pad detection using the drone's downward-facing camera.
  - Perform specific actions (e.g., flips) based on pad IDs.
  - Navigate a linear path to detect up to four mission pads.

---

## **Getting Started**

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/your-username/drone-lab-repo.git
   cd drone-lab-repo
   ```

2. **Setup Instructions**:
   - Ensure you have a Tello drone and the **TelloLib** library installed.
   - Configure your development environment for Java (e.g., IntelliJ IDEA or Eclipse).
   - Use a Wi-Fi-enabled computer to connect to the drone.

3. **Run the Projects**:
   - Navigate to the desired lab folder and open the corresponding Java file.
   - Follow the in-code comments and instructions to execute the program.

---

## **How It Works**

Each project is written with modular code and detailed comments to make learning straightforward. The labs incorporate concepts such as threading, graphical interfaces, and drone-specific commands, helping you develop a strong understanding of drone programming and control.

---

## **Contributors**

This repository was contrubited by:  
- **Venus Dinari**  
- **Althea Aguel**  
- **Hossein Valavi**  
- **Habeba Hossain**

We collaborated to design and implement these projects as part of our drone programming exploration.

---

Happy flying! 🚁
