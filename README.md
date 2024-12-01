# Traffic Signal Controller Using 8086 Microprocessor 🚦  

This project implements a **microprocessor-based traffic signal controller** using the **8086 microprocessor**, programmed in **assembly language**, and simulated in **Proteus Design Suite**. It manages a four-way intersection, incorporating features such as two-phase control and priority-based traffic management.

---

## 📌 Project Overview  

The **Traffic Signal Controller** is designed to:  
- Simulate real-world traffic light behavior.  
- Provide efficient traffic management using assembly-level programming.  
- Incorporate features like emergency vehicle priority.  

This project highlights the integration of software (assembly code) and hardware (microprocessor components) to build a functional traffic management system.

---

## 🛠️ Components Used  

### Hardware Simulated in Proteus:  
1. **8086 Microprocessor**: Executes the assembly program to control traffic signals.  
2. **8255A Programmable Peripheral Interface (PPI)**: Controls the LEDs based on microprocessor commands.  
3. **LEDs (Red, Yellow, Green)**: Represent the traffic signals.  
4. **74ALS138 Decoder**: Handles address decoding for smooth communication.  
5. **74LS373 Latches**: Stabilize signals from the 8255A for consistent LED output.  
6. **Resistors**: Protect LEDs from excessive current.  
7. **Connecting Wires**: Interconnect components.  

---

## ⚙️ System Features  

### Traffic Control Modes:  
1. **Two-Phase System**:  
   - Alternates green and red lights between north-south and east-west directions.  
   - Includes yellow light transitions for safety.  

2. **Priority-Based System**:  
   - Assigns priority to specific directions, such as emergency lanes.  
   - Implements individual direction green light phases.  

### Functionality:  
- Designed using **8086 assembly language** for precise timing and control.  
- Simulated in **Proteus** for hardware accuracy and validation.  

---

## 📂 Project Structure  

- `assemblyprog.txt`: Contains the 8086 assembly language code for traffic signal control.  
- `Traffic_controller_using8086.pdsprj`: Proteus project file for simulation.  
- `Traffic_controller_using8086.pdsprj.ARYAN.aryan.workspace`: Workspace settings for Proteus.  
- `noname.exe`: Executable file of the assembled program.  
- `README.md`: This documentation file.  

---

## 🚀 How to Run the Simulation  

1. Open the `.pdsprj` file in **Proteus Design Suite**.  
2. Ensure all components are correctly connected as per the circuit diagram.  
3. Load the assembly program (`assemblyprog.txt`) onto the 8086 microprocessor.  
4. Run the simulation and observe the traffic light transitions and timing.  

---

## 📖 Learning Outcomes  

- Mastered **8086 microprocessor architecture** and assembly language programming.  
- Built proficiency in using **Proteus** for designing and simulating hardware systems.  
- Gained practical experience in creating real-world traffic management solutions.  

---

## 🧑‍💻 Authors  

- **Aryan Kanojia** (2K22/EC/56)  
- **Aditya Jain** (2K21/EC/15)  
- **Akshat Gupta** (2K21/EC/19)  
- **Kartik** (2K21/EC/114)  

---

## 📬 Feedback and Contributions  

We welcome your feedback and suggestions for improving this project. Feel free to reach out or fork the repository to contribute!  

---

## 🏷️ Tags  
`8086 Microprocessor` `Assembly Language` `Traffic Signal Controller` `Proteus Simulation` `College Project`
