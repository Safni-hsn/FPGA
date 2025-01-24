# FPGA Projects

This repository showcases my FPGA-based projects, including a Pong Game and a Mini Traffic Light Controller. These projects demonstrate my expertise in FPGA development using VHDL, with simulations performed in Vivado and Quartus Prime for different hardware platforms.

---

## 📌 Projects Overview

### 1. **Pong Game**
This is a classic Pong Game implemented in VHDL and designed for the **Basys 3 FPGA board**. It features real-time player interaction, paddle movement, and ball physics, making it a fun and interactive project.

#### **Features**
- Two-player controls for paddle movement.
- Ball movement with collision detection and boundary checks.
- Score tracking for competitive gameplay.

#### **Implementation Details**
- Designed with a finite state machine (FSM) for paddle movement and ball physics.
- The VGA controller handles graphical output for the game display.
- Includes a testbench for verifying game logic.
- Simulated and implemented using **Vivado**.

#### **Instructions to Run**
1. Open the Vivado project for the Pong Game.
2. Synthesize and implement the design for the Basys 3 FPGA board.
3. Generate the bitstream file and program the board.
4. Connect a VGA monitor to the Basys 3 and use the on-board buttons or switches to control the paddles.

---

### 2. **Mini Traffic Light Controller**
This project simulates a real-world traffic light system, implemented in VHDL and designed for the **DE10-Lite FPGA board**. It features traffic light control and pedestrian crossing logic, demonstrating the use of finite state machines.

#### **Features**
- Traffic light sequence with red, yellow, and green lights.
- Pedestrian crossing logic integrated with the system.
- Configurable timing intervals for the lights.

#### **Implementation Details**
- Uses a finite state machine (FSM) to handle light transitions and pedestrian states.
- LEDs on the DE10-Lite board are used to simulate the traffic lights.
- Includes a testbench for validating the logic.
- Simulated and implemented using **Quartus Prime**.

#### **Instructions to Run**
1. Open the Quartus Prime project for the Mini Traffic Light Controller.
2. Compile the design and generate the programming file for the DE10-Lite FPGA board.
3. Program the DE10-Lite board with the compiled file.
4. Observe the traffic light sequence through the LEDs on the board.

---

## 🛠 Tools and Technologies

### Pong Game:
- **HDL**: VHDL
- **Simulation Tools**: Vivado
- **Hardware**: Basys 3 FPGA Board

### Mini Traffic Light Controller:
- **HDL**: VHDL
- **Simulation Tools**: Quartus Prime
- **Hardware**: DE10-Lite FPGA Board

---

## 📷 Project Demos

### Pong Game
![WhatsApp Image 2025-01-24 at 21 05 53_5e7d8eef](https://github.com/user-attachments/assets/e531ff1b-c027-429c-b8a0-1bac64ff2309)


### Mini Traffic Light Controller
![Uploading sddefault.jpg…]()


*(Add actual screenshots or GIFs of your projects here to make the README more engaging.)*

---

## 🗂 Project Structure

